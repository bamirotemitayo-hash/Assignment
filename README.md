# Task Manager Flutter App

## Overview

Task Manager is a simple Flutter-based mobile application developed as part of a **Mobile Engineering assignment**. The app allows users to create, view, complete, and delete tasks using an intuitive interface. The application uses **no backend, database, or local storage** — all data exists only while the app is running, as required by the assignment.

---

##  Assignment Objectives Met

This project satisfies all stated assignment requirements:

* Built using **Flutter (Dart)**
*  Android-focused implementation
*  No backend or database usage
*  Tasks stored temporarily in memory
*  Multiple screens with navigation
*  Proper use of required Flutter widgets
*  Clean UI and user-friendly interactions

---

## Application Features

* Add new tasks with:

    * Title (required)
    * Description
    * Priority (Low / Medium / High)
* View all tasks in a scrollable list
* Mark tasks as completed
* View detailed task information
* Delete tasks with confirmation dialog
* Visual feedback using SnackBars

---

## 🧩 Screens Implemented

1. **Splash / Welcome Screen**

    * Displays welcome message
    * Automatically navigates to Home Screen

2. **Home Screen**

    * Displays list of tasks using `ListView`
    * Each task displayed inside a `Card`
    * Floating Action Button to add tasks

3. **Add Task Screen**

    * Uses `Form` and `TextFormField`
    * Validates required input
    * Returns task data to Home Screen

4. **Task Detail Screen**

    * Displays full task information

---

## Widgets & Concepts Used

* `Scaffold`
* `AppBar`
* `ListView`
* `Card`
* `FloatingActionButton`
* `TextFormField`
* `SnackBar`
* `AlertDialog`
* `Navigator.push()` and `Navigator.pop()`
* `StatefulWidget` and `setState()`

---

##  Project Structure

```
lib/
 ├── main.dart
 ├── models/
 │    └── task.dart
 └── screens/
      ├── splash_screen.dart
      ├── home_screen.dart
      ├── add_task_screen.dart
      └── task_detail_screen.dart
```

---

##  How to Run the App

1. Ensure Flutter is installed and configured
2. Connect an Android phone or start an emulator
3. Clone this repository:

```
git clone <your-github-repo-link>
```

4. Navigate to the project folder and run:

```
flutter pub get
flutter run
```

---

##  Screenshots

Screenshots of the application in use are available in the following directory:

```
assets/screenshots/
```

---

##  Key Learning Outcomes

* Understanding Flutter widget tree
* Managing UI state with `setState`
* Navigating between screens
* Form validation and user feedback
* Structuring a Flutter project properly

---

## 👤 Author

**Temitayo Bamiro**
Mobile Engineering – Flutter Assignment

---

##  License

This project is developed strictly for **academic purposes**.
