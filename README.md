
#  Task Manager App

## SEN4302 — Mobile Application Development
### Assignment 03

---

# Project Overview

The **Task Manager App** is a native Android application developed using Kotlin.  
This project demonstrates modern Android development practices such as MVVM architecture, state management using ViewModel, local data persistence with DataStore, and efficient UI rendering using RecyclerView.

The application allows users to create, manage, update, and delete personal tasks with persistent local storage.

---

#  Project Objectives

- Apply MVVM architecture in Android development
- Implement local data persistence
- Handle configuration changes (screen rotation)
- Use modern Android components (ViewModel, RecyclerView, Coroutines)
- Build a clean and user-friendly Material Design interface

---

#  Features

- ✅ Add new task (title, description, priority)
- ✅ View all tasks in a RecyclerView list
- ✅ Edit existing tasks
- ✅ View detailed task information
- ✅ Mark tasks as completed or active
- ✅ Delete tasks with confirmation dialog
- ✅ Filter tasks (All / Active / Completed)
- ✅ Data persistence after app restart
- ✅ State preservation during screen rotation
- ✅ Empty state display when no tasks exist
- ✅ Material Design UI

---

#  Architecture

This project follows the **MVVM (Model–View–ViewModel)** pattern.

## Model
- `Task.kt`
- `TaskRepository.kt`

## View
- `MainActivity`
- `AddEditTaskActivity`
- `TaskDetailActivity`
- XML layout files

## ViewModel
- `TaskViewModel.kt`

### Why MVVM?
- Clear separation of concerns
- Better code organization
- Improved maintainability
- Easier testing

---

#  Data Persistence

The app uses **DataStore Preferences** for local storage.

### Why DataStore?
- Asynchronous and coroutine-based
- Modern replacement for SharedPreferences
- Safe and efficient
- Recommended for new Android apps

Tasks are serialized to JSON using Gson before storage.

---

#  State Management

- ViewModel ensures UI data survives configuration changes
- No data loss during screen rotation
- Efficient state handling

---

#  Technical Stack

| Component | Technology |
|------------|------------|
| Language | Kotlin |
| Min SDK | API 26 (Android 8.0) |
| Target SDK | API 34 |
| Architecture | MVVM |
| State Management | ViewModel + LiveData |
| Local Storage | DataStore Preferences |
| UI Layout | XML + Material Components |
| List Handling | RecyclerView + DiffUtil |
| Async Processing | Kotlin Coroutines |
| Serialization | Gson |

---


---

#  How to Run

1. Clone the repository
2. Open the project in Android Studio
3. Wait for Gradle sync
4. Run on emulator or physical device (API 26+)

---

#  Screenshots

##  Add Task
![Add Task](https://github.com/tharindu002/Task-Manager/blob/9f767255ac51ae7898cb31a2b7b6a8b61bfc5911/ss/AddTask.png)

---

##  Delete Task (Portrait)
![Delete Task](https://github.com/tharindu002/Task-Manager/blob/9f767255ac51ae7898cb31a2b7b6a8b61bfc5911/ss/DeleteTask-2.png)

![Delete Task 2](https://github.com/tharindu002/Task-Manager/blob/9f767255ac51ae7898cb31a2b7b6a8b61bfc5911/ss/DeleteTask.png)

---

##  Delete Task (Landscape)
![Landscape Delete 1](https://github.com/tharindu002/Task-Manager/blob/e67f108974aa9e26d46d9b984d1b0274cbeb782f/ss/Porttrate%20Delete.png)

![Landscape Delete 2](https://github.com/tharindu002/Task-Manager/blob/e67f108974aa9e26d46d9b984d1b0274cbeb782f/ss/Porttrate%20TaskUpdate.png)

---

##  Update Task (Portrait)
![Portrait Update](https://github.com/tharindu002/Task-Manager/blob/9f767255ac51ae7898cb31a2b7b6a8b61bfc5911/ss/UpdateTask.png)

---

##  Add Task (Portrait)
![Portrait Add](https://github.com/tharindu002/Task-Manager/blob/561cf8790e96625986374f61220408ac2d7e503c/ss/Porttrate%20taskAdd.png)

---

##  Task List
![Task List](https://github.com/tharindu002/Task-Manager/blob/9f767255ac51ae7898cb31a2b7b6a8b61bfc5911/ss/TaskList.png)

#  Student Information

- **Student Name:** A M T N E Banadra
- **Student ID:** 11267
- **Course:** SEN4302 – Mobile Application Development
- **Assignment:** 03

---






