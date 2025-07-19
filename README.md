


Setup Instructions
Step 1: Clone the Repository
bash
Copy
Edit
git clone <repo_url>
cd fastapi_kpa
Step 2: Set Up Virtual Environment
bash
Copy
Edit
python -m venv env
.\env\Scripts\activate   # Windows
Step 3: Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt


# KPA Assignment API (FastAPI)

This project implements a backend API for capturing and managing inspection data related to **bogie checksheets** and **wheel specifications** for railway KPA forms.

---

##  Features

-  Submit **Bogie Checksheet** data via POST API
-  Submit **Wheel Specification** data via POST API
-  Retrieve all submitted records via GET API
-  PostgreSQL database integration
-  Modular FastAPI architecture
-  Pydantic validation for schemas

---

##  Tech Stack

- **Backend Framework**: FastAPI
- **Language**: Python 3.11+
- **Database**: PostgreSQL
- **ORM**: SQLAlchemy
- **Dependency Management**: `venv`, `pip`
- **Testing Tools**: Postman

---

