
# 🩸 Blood Bank Services Manager

## 📌 Overview
The **Blood Bank Services Manager** is a web-based application designed to streamline the management of blood donation and transfusion services. It connects donors, recipients, and hospitals, facilitating efficient blood inventory management and request processing.

## 🚀 Features
- **User Registration & Authentication**: Separate portals for donors, recipients, and hospital staff.
- **Blood Inventory Management**: Real-time tracking of blood types and quantities available.
- **Blood Donation Scheduling**: Donors can schedule appointments for blood donation.
- **Blood Request Handling**: Recipients and hospitals can request specific blood types; admins can approve or decline requests.
- **Notification System**: Automated notifications for donation reminders, request approvals, and more.
- **Reporting**: Generate reports on donations, requests, and inventory levels.

## 📂 Project Structure
```
📦 Blood-Bank-Services-Manager
 ┣ 📂 donor/                   # Donor-related functionalities
 ┣ 📂 patient/                 # Patient (recipient) functionalities
 ┣ 📂 static/                  # Static files (CSS, JavaScript, images)
 ┣ 📂 templates/               # HTML templates
 ┣ 📜 db.sqlite3               # SQLite database file
 ┣ 📜 manage.py                # Django project management script
 ┣ 📜 requirements.txt         # Python dependencies
 ┗ 📜 README.md                # Project documentation
```

## 🛠️ Technologies Used
- **Frontend**:
  - HTML
  - CSS
  - JavaScript
- **Backend**:
  - Python
  - Django Framework
- **Database**:
  - SQLite (default for Django; can be switched to PostgreSQL or MySQL)
- **Additional Libraries**:
  - Django Rest Framework (for API endpoints)
  - jQuery (for enhanced frontend interactions)

## ▶️ Getting Started

### Prerequisites
- Python 3.x installed on your system.
- Virtual environment tool (optional but recommended).

### Installation Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/sandeepbakkireddy/Blood-Bank-Services-Manager.git
   cd Blood-Bank-Services-Manager
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python -m venv env
   # On Windows
   env\Scripts\activate
   # On macOS/Linux
   source env/bin/activate
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations**:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create a superuser account** (for admin access):
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**:
   ```bash
   python manage.py runserver
   ```

7. **Access the application**:
   Open your web browser and navigate to `http://127.0.0.1:8000/`.

## 🛡️ Security Considerations
- **Authentication**: Ensure that user passwords are stored securely using Django's built-in authentication system.
- **Authorization**: Implement proper permission checks to restrict access to sensitive functionalities.
- **Data Validation**: Validate all user inputs to prevent SQL injection and other security vulnerabilities.
- **HTTPS**: In a production environment, configure HTTPS to encrypt data transmitted between clients and the server.



![Screenshot 2025-03-07 145107](https://github.com/user-attachments/assets/e60c9ae2-385f-4c85-acb0-232f4243ad22)
![Screenshot 2025-03-07 145055](https://github.com/user-attachments/assets/0982b5b2-78c5-4463-9c83-5263ec52607f)
![Screenshot 2025-03-07 145044](https://github.com/user-attachments/assets/caccafa4-c3e3-4954-bd44-82c4d7bc2004)
![Screenshot 2025-03-07 145027](https://github.com/user-attachments/assets/4c68925b-f741-4764-ab1c-988387f25b35)
