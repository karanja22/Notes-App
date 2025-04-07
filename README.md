# Notes App

## Introduction
The Notes App is a cross-platform application that enables users to create, manage, and organize notes seamlessly. It features a Django backend for data management and a Flutter frontend for an intuitive user experience.

## Key Features
- **User Accounts**: Secure login and registration for personalized note management.
- **Note Management**: Create, edit, delete, and view notes effortlessly.
- **Search Functionality**: Quickly locate notes using a built-in search feature.
- **Responsive Design**: Optimized for both web and mobile devices.

## Architecture
This application follows a client-server architecture:
- **Backend**: Django handles data storage and business logic.
- **Frontend**: Flutter provides a responsive UI for users.

## Technologies
- **Django**: For building the backend API.
- **Flutter**: For developing the cross-platform frontend.
- **SQLite**: For lightweight data storage (or specify your database if different).

## Getting Started

### Prerequisites
- Python 3.x
- Node.js (for Flutter)
- Flutter SDK

### Installation Steps

#### 1. Clone the Repository
```bash
git clone https://github.com/karanja22/Notes-App.git
```

#### 2. Backend Setup
Navigate to the Django backend directory:
```bash
cd Notes-App/DjangoBackend
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Run database migrations:
```bash
python manage.py migrate
```
Start the Django server:
```bash
python manage.py runserver
```

#### 3. Frontend Setup
Navigate to the Flutter frontend directory:
```bash
cd Notes-App/FlutterFrontend
```
Get Flutter dependencies:
```bash
flutter pub get
```
Launch the Flutter application:
```bash
flutter run
```

## Usage
1. Access the backend at http://localhost:8000 (or your specified port).
2. Use the Flutter app to interact with your notes, allowing you to create, view, and manage them.


## Directory Structure
```basic
Notes-App/
├── DjangoBackend/          # Django backend files
│   ├── manage.py           # Project management script
│   ├── requirements.txt    # Dependencies for Python
│   └── [other files]       # Additional Django components
└── FlutterFrontend/        # Flutter frontend files
    ├── lib/                # Dart source code
    ├── pubspec.yaml        # Flutter dependencies
    └── [other files]       # Additional Flutter components
```
## Contact Information
For any questions or feedback, please reach out to:

- **Email**: frasiahnyambyra22@gmail.com  
- **GitHub**: [karanja22](https://github.com/karanja22)
