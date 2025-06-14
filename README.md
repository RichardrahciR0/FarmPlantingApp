# Farm Planting App

Welcome to the Farm Planting App – a mobile tool designed to help farmers, gardeners, and orchard owners easily **plan, manage, and visualise** their farm layouts and day-to-day tasks.

This project was built as part of our final year Capstone project in collaboration with **Orefox AI Limited**. The goal was to create a user-friendly app that supports smart and sustainable agriculture, no matter your level of experience.

---

##  What the App Can Do

- **Plan your farm layout** using an easy drag-and-drop editor
- **View your crops on a real-world map** with location markers
- **Check the weather** to help decide when to water or harvest
- **Create and track tasks** like planting, fertilising, and pruning
- **Sign up and log in securely** using JWT-based authentication
- **Set up your profile** and personalise the app to your needs



## Built With

- **Frontend**: Flutter (Dart)
- **Backend**: Django REST Framework
- **Authentication**: Djoser + JWT
- **Secure Storage**: flutter_secure_storage
- **Database**: PostgreSQL
- **Version Control**: GitHub



##  How to Run the App

1. Backend

```bash
git clone https://github.com/your-username/farm-planting-backend.git
cd farm-planting-backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

2. Frontend

git clone https://github.com/your-username/farm-planting-frontend.git
cd farm-planting-frontend
flutter pub get
flutter run

