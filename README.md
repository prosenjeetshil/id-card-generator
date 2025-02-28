# ID Card Generation System

## 📌 Project Overview
ID Card Generation System is a full-stack web application designed to streamline the process of generating and managing ID cards for colleges. Built using **React** for the frontend and **Django** for the backend, it provides role-based access control, bulk ID card generation, and temporary ID issuance.

## 🛠 Tech Stack
- **Frontend:** React.js, Bootstrap / Tailwind CSS
- **Backend:** Django, Django REST Framework (DRF)
- **Database:** PostgreSQL / SQLite (for development)
- **Authentication:** JWT-based authentication
- **Deployment:** Docker, Vercel (Frontend), Heroku/Railway (Backend)

## ✨ Features
- 🔑 **User Authentication & RBAC:** Admins, Staff, and Students have different access levels.
- 🆔 **ID Card Generation:** Generate unique ID cards with QR codes.
- 📑 **Bulk ID Generation:** Upload a CSV file to generate multiple ID cards at once.
- ⏳ **Temporary ID Issuance:** Issue temporary ID cards for students and staff.
- 📊 **Dashboard & User Management:** Admin dashboard for managing users and ID cards.
- 📡 **REST API:** Secure API endpoints for managing ID cards and user authentication.

## 🚀 Installation & Setup
### 1️⃣ Backend Setup (Django)
```bash
# Clone the repository
git clone https://github.com/prosenjeetshil/id-card-generator.git
cd id-card-generator/backend

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create a superuser
python manage.py createsuperuser

# Run the server
python manage.py runserver
```

### 2️⃣ Frontend Setup (React)
```bash
cd ../frontend

# Install dependencies
yarn install  # or npm install

# Start the React app
yarn start  # or npm start
```

## 🎯 Future Enhancements
- ✅ Email notifications for generated IDs.
- ✅ ID verification via QR scanning.
- ✅ Integration with college management systems.

## 🤝 Contributing
Pull requests are welcome! Feel free to open an issue for feature requests or bug reports.

## 📄 License
This project is licensed under the MIT License.

---
**⭐ If you find this project useful, don't forget to star the repository!**
