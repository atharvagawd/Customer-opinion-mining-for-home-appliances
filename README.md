# Customer Opinion Mining for Home Appliances (HomeTech Appliances)

One web application integrating **ASMA** (NLP opinion mining), **Enterprise Systems** (roles, workflow, dashboard, database) and **ITPM** (charter, WBS, Gantt, tasks, risks, tests).

## Requirements
Python 3.9+ and an internet connection for the Chart.js CDN (charts only). No database server or API keys needed.

## Install and run
```bash
cd consumer-opinion-mining
python -m venv venv
venv\Scripts\activate          # Windows   (Mac/Linux: source venv/bin/activate)
pip install -r requirements.txt
python backend/seed.py         # optional: recreate database/hometech.db with 110 reviews (also runs automatically on first start)
python backend/app.py
```
Open **http://localhost:5000** (the Flask server serves the frontend too).

## Demo logins
| Role | Email | Password |
|---|---|---|
| Customer | customer@hometech.com | Customer@123 |
| Analyst | analyst@hometech.com | Analyst@123 |
| Product Manager | manager@hometech.com | Manager@123 |
| Administrator | admin@hometech.com | Admin@123 |

## Demonstration flow
1. Login as Customer → Submit Review → choose *LG Refrigerator* → Submit Review → **Analyze Review** (pipeline, sentiment, aspects, opinions, keywords shown; stored in DB).
2. Logout, login as Product Manager → Dashboard → recurring complaints → Product Comparison (e.g. Samsung vs LG Refrigerator).
3. Issue Management → issues marked *Under Review* / *In Progress*; change a status.
4. Reports → view, Download CSV, Print / Save PDF.
5. IT Project Management → Charter, WBS, Gantt, Tasks, Team, Risks, Testing (Run all tests).
6. Subject Integration page maps every feature to ASMA / ES / ITPM.

## Tests
`python tests/test_asma.py` (NLP unit tests). System/API tests run from ITPM → Testing → *Run all tests*.

## Reset data
`python backend/seed.py` recreates the database. MySQL/PostgreSQL: run `database/schema.sql` (replace `AUTOINCREMENT` with `AUTO_INCREMENT`/`SERIAL`) and point `backend/services.py:connect()` at the new driver.

Docs are in `docs/`.
