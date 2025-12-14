# Android To-Do List Application (2Do)

## Project Overview

My Project is a simple Android to-do list application. The app allows users to:

- Add new tasks

- Display tasks in a ListView

- Mark tasks complete/incomplete using a CheckBox

- Delete tasks via long-press

- Persist data locally using SQLite

### User Interface Design and Layouts
The user interface is built using XML layout files and standard Android UI components:
ListView 
EditText
Button 
CheckBox

### Event-Driven Programming
The application responds to user interactions through event listeners, including OnClickListener for adding tasks and OnItemLongClickListener for deleting tasks.

### Custom Adapter Usage
A custom adapter is used to bind task data to the ListView, allowing dynamic updates to the UI when tasks are added, modified, or removed.

### Local Data Persistence with SQLite
Task data is stored locally using SQLite to ensure persistence across app restarts. The implementation includes database creation and basic CRUD operations.

### Activity Lifecycle Awareness
2Do is designed with awareness of the Android activity lifecycle to ensure that user data remains consistent during configuration changes and lifecycle events.
