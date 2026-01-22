<p align="right">
<a href="https://github.com/DjangoCRM/django-crm/blob/main/README.md">English</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-hindi.md">हिन्दी</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-spanish.md">Español</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-chinese.md">中文</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-portuguese.md">Português</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-arabic.md">اَلْعَرَبِيَّةُ</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-french.md">Français</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-german.md">Deutsch</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-dutch.md">Nederlands</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-italian.md">Italiano</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-ukrainian.md">Українська</a>
</p>

---

# Django-CRM

Django-CRM (Collaborative & Analytical CRM)
Developed & Maintained by Sankalp Singh Final Year MCA Student at Ramdeobaba University AIML Developer & Data Analyst at SS Infotech

🚀 Project Overview
Django-CRM is a mature, open-source Customer Relationship Management solution designed to provide enterprise-level business tools with a focus on simplicity and customizability. It serves as a comprehensive "Digital Brain" for businesses, integrating sales tracking, team collaboration, and data analytics into a single self-hosted platform.

🛠 Features
🤝 Collaborative CRM
Team Tasks & Projects: Efficiently manage workloads by assigning tasks and subtasks to team members.

Internal Chat Integration: Discuss specific deals or tasks directly within the application to keep communication organized.

Office Memos: Streamline internal announcements and convert them into actionable projects.

Role-Based Access Control: Securely manage user permissions based on their specific role in the company.

📊 Analytical CRM
Sales Analytics: Gain actionable insights with built-in reports like sales funnels and income summaries.

Lead Source Analysis: Identify where your most valuable customers are coming from.

Sales Forecasting: Track deals and predict future revenue with high accuracy.

📧 Communication & Automation
Automated Email Sync: Automatically capture and organize correspondence related to specific leads and deals.

Email Marketing: Manage bulk mailing campaigns and personalized newsletters directly from the CRM.

VoIP Integration: Contact clients via VoIP directly from deal instances.

💻 Technical Stack
Language: <img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/site/icons/python-logo.svg" width="20" height="20"> Python 3.10+

Framework: <img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/site/icons/django-logo.svg" width="20" height="20"> Django 5.1+ (LTS)

Database Support: SQLite3 (Dev), MySQL 8.0+, and PostgreSQL 14+

UI/UX: Custom adaptive Admin HTML templates and Jazzmin for a modern dashboard experience.

⚙️ Getting Started
1. Prerequisites
Ensure you have Python installed on your system.

Bash
python --version  # Should be 3.10 or higher
2. Installation
Bash
# Clone the repository
git clone https://github.com/sankalpG007/CRM-Django-.git
cd CRM-Django-

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
3. Database Setup
Bash
python manage.py migrate
python manage.py loaddata groups.json  # Initial population of user groups
python manage.py createsuperuser
4. Run the Application
Bash
python manage.py runserver
Access the dashboard at http://127.0.0.1:8000/en/456-admin/ (or your configured admin path).

👨‍💼 About the Maintainer
Sankalp Singh As an AIML Developer and Data Analyst at SS Infotech, I have customized this CRM to enhance its analytical capabilities and user interface. This project serves as a cornerstone of my final year MCA studies at Ramdeobaba University, demonstrating expertise in full-stack Django development and business intelligence systems.
