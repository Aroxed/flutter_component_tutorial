# Flutter Component Tutorial

A simple Todo List application that demonstrates Flutter component composition and data exchange patterns.

## Features

- Add new todo items
- Mark todos as complete/incomplete
- Delete todos
- Clean and maintainable component structure
- Demonstrates various Flutter patterns for component communication

## Project Structure

```
lib/
├── models/
│   └── todo_item.dart      # Data model for todo items
├── widgets/
│   ├── todo_item_widget.dart   # Widget for displaying a single todo
│   └── add_todo_form.dart      # Form widget for adding new todos
└── main.dart               # Main application file
```

## Component Communication Patterns

This project demonstrates several important Flutter patterns:

1. **Callback Pattern**
   - Child-to-parent communication using callbacks
   - Example: `TodoItemWidget` uses `onToggle` and `onDelete` callbacks

2. **State Management**
   - Local state management using `setState`
   - State is maintained in the parent component and passed down to children

3. **Form Handling**
   - Text input management using `TextEditingController`
   - Form submission handling

## Getting Started

### Prerequisites

- Flutter SDK (latest version recommended)
- Dart SDK
- IDE (VS Code, Android Studio, or IntelliJ IDEA)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Aroxed/flutter_component_tutorial
cd flutter_component_tutorial
```

2. Get dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Usage

1. Add a new todo:
   - Type your todo in the text field at the top
   - Press Enter or click the "Add" button

2. Manage todos:
   - Click the checkbox to toggle completion status
   - Click the delete icon to remove a todo

## Architecture

The application follows a simple but effective architecture:

- **Models**: Data classes that represent the application's data structure
- **Widgets**: Reusable UI components
- **Screens**: Container components that manage state and compose other widgets

## Contributing

Feel free to submit issues and enhancement requests!
