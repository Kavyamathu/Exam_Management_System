# 🎓 Exam Management System

A complete online exam management system built with Django REST Framework and React.

## ✨ Features

### For Students:
- User registration and authentication
- View upcoming exams
- Take timed exams
- View detailed results
- Track completed exams
- Receive notifications
- Profile management

### For Admins:
- Dashboard with statistics
- Create and manage exams
- Build question banks
- View performance analytics
- Track top scorers
- Monitor pass/fail ratios

### Automatic Notifications:
- Registration welcome email
- Exam scheduled alerts
- Exam reminders (1 week & 1 day before)
- Result published notifications

## 🛠️ Tech Stack

**Backend:**
- Django 6.0.2
- Django REST Framework
- SQLite Database
- Token Authentication

**Frontend:**
- React 18
- React Router DOM
- Axios
- Custom CSS

## 🚀 Installation

### Prerequisites:
- Python 3.12+
- Node.js 16+
- npm

### Backend Setup:

```bash
cd backend/exam
pip install django djangorestframework django-cors-headers
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

### Frontend Setup:

```bash
cd my_app
npm install
npm start
```

## 🔐 Default Credentials

**Admin:**
- Username: `admin`
- Password: `admin123`

**Students:**
- Username: `student1` / Password: `password123`
- Username: `student2` / Password: `password123`
- Username: `student3` / Password: `password123`

## 📊 Sample Data

Run this to create sample data:

```bash
cd backend/exam
python setup_sample_data.py
```

This creates:
- 3 candidate accounts
- 4 exams with different dates
- 14 questions (10 Python + 4 Java)
- 21 notifications

## 🎯 Usage

1. Open: `http://localhost:3000`
2. Login with credentials
3. Students can take exams
4. Admins can manage exams and questions
5. View results and analytics

## 📱 Pages

1. Landing Page
2. Registration
3. Login
4. Admin Dashboard
5. Manage Exams
6. Question Bank
7. Candidate Dashboard
8. Exam Page (with timer)
9. Result Page
10. Analytics
11. Profile
12. Notifications

## 📧 Email Notifications

Emails are configured to print to console for testing.

To use real email (Gmail):
1. Update `backend/exam/exam/settings.py`
2. Add your Gmail credentials
3. Use App Password (not regular password)

## 🎨 Features Highlights

- ✅ Live countdown timer during exams
- ✅ Automatic score calculation
- ✅ Pass/Fail determination
- ✅ Detailed answer review
- ✅ Multiple exam attempts allowed
- ✅ Responsive design
- ✅ Beautiful UI with animations

## 📝 License

This project is for educational purposes.

## 👨‍💻 Author

Created as a complete exam management solution.

## 🙏 Acknowledgments

Built with Django and React for modern web development.
