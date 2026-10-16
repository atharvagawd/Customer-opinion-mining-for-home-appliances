# 🏠 Customer Opinion Mining for Home Appliances

An integrated academic project combining **Advanced Social Text and Media Analysis (ASMA), Enterprise Systems (ES), and IT Project Management (ITPM)** to analyze customer reviews, identify product issues, and support data-driven business decisions.

## 📌 Project Overview

Customers share opinions about home appliances through online reviews. Analyzing these reviews manually can be time-consuming and make it difficult to identify recurring problems.

This project provides a web-based system that analyzes customer reviews, identifies sentiment and product-related aspects, detects recurring complaints, and presents useful insights through dashboards and reports.

The project demonstrates how text analytics can be integrated with enterprise information management and IT project management practices.

## 🎯 Objectives

- Analyze customer reviews of home appliances.
- Identify positive, negative, mixed, and neutral opinions.
- Extract product-related aspects and their associated sentiments.
- Detect recurring customer complaints and product issues.
- Provide dashboards, analytics, product comparisons, and reports.
- Demonstrate the integration of ASMA, ES, and ITPM concepts.

## ✨ Key Features

- **Sentiment Analysis:** Classifies customer opinions based on sentiment.
- **Aspect-Based Opinion Mining:** Analyzes opinions about aspects such as price, noise, design, durability, and performance.
- **Review Management:** Collects and manages customer reviews.
- **Issue Detection:** Helps identify recurring product complaints.
- **Role-Based Access:** Supports different user roles, including Customer, Analyst, Product Manager, and Administrator.
- **Analytics Dashboard:** Presents review statistics and product insights.
- **Product Comparison:** Helps compare products based on customer feedback.
- **Reports:** Provides summarized information to support business decisions.
- **ITPM Module:** Includes project planning and management features such as the Project Charter, Work Breakdown Structure (WBS), Gantt chart, task management, risk register, and testing records.

## 📚 Integration of Three Subjects

### 1. Advanced Social Text and Media Analysis (ASMA)

ASMA is used to process and analyze customer review text.

- Text preprocessing and normalization
- Sentiment classification
- Aspect and opinion analysis
- Identification of positive and negative product feedback
- Analysis of mixed opinions within a review

### 2. Enterprise Systems (ES)

ES manages the business information and workflows associated with customer reviews.

- Centralized management of users, products, and reviews
- Storage of review analysis results
- Role-based access control
- Product issue tracking and status management
- Dashboards, analytics, product comparison, and reports

### 3. IT Project Management (ITPM)

ITPM demonstrates how the software project is planned, organized, monitored, and tested.

- Project Charter and Scope
- Work Breakdown Structure (WBS)
- Gantt chart and project scheduling
- Task and team management
- Risk Register
- Testing and quality assurance

**In summary:** ASMA analyzes customer opinions, ES manages the business information and processes, and ITPM manages the development project.

## 🛠️ Technology Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite
- **Data Visualization:** Chart.js
- **Analysis:** Lexicon-based sentiment analysis and rule-based text processing

## ⚙️ Installation and Setup

### Prerequisites

- Python 3 installed
- pip package manager
- A modern web browser

### Steps to Run Locally

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/Customer-opinion-mining-for-home-appliances.git
```

Replace `YOUR-USERNAME` with your GitHub username.

**2. Navigate to the project directory**

```bash
cd Customer-opinion-mining-for-home-appliances
```

**3. Create a virtual environment**

```bash
python -m venv venv
```

**4. Activate the virtual environment**

On Windows:

```bash
venv\Scripts\activate
```

On macOS or Linux:

```bash
source venv/bin/activate
```

**5. Install dependencies**

```bash
pip install -r requirements.txt
```

**6. Start the application**

For the project version in which the Flask entry point is `backend/app.py`:

```bash
python backend/app.py
```

**7. Open the application**

Open the local URL displayed in the terminal. If the application uses the default port, visit:

`http://localhost:5000`

Refer to the project files and documentation if your final folder structure or startup command differs.

## 🧪 Testing

The project includes tests for validating the analysis functionality and application workflows.

To run the ASMA tests, if the test file is present at the specified path:

```bash
python tests/test_asma.py
```

Follow the project documentation for any additional integration or system tests.

## 💡 Expected Outcome

The system helps users understand customer feedback more efficiently by organizing reviews into meaningful sentiment and aspect-level insights. It also helps product managers identify recurring issues and make informed decisions using centralized information and analytics.

## 🎓 Academic Project

**Project Title:** Customer Opinion Mining for Home Appliances

**Subjects Integrated:**
- Advanced Social Text and Media Analysis (ASMA)
- Enterprise Systems (ES)
- IT Project Management (ITPM)

Developed for academic learning and demonstration of text analytics, enterprise information management, and IT project management concepts.

## 👥 Contributors

Add your project team members' names here.

## 📄 License

This project is intended for academic and educational purposes. Add a license if you intend to specify conditions for reuse and distribution.
