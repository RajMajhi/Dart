````
# Dart Programming Language

Dart is a modern, open-source programming language developed by Google. It is optimized for building fast, cross-platform applications for mobile, web, desktop, and server. Dart is best known as the language used by Flutter.

---

## 🚀 Features

- Object-oriented and strongly typed
- Null safety support
- Just-In-Time (JIT) and Ahead-Of-Time (AOT) compilation
- Fast performance
- Cross-platform development support
- Clean and readable syntax

---

## 📦 Installation

### 1️⃣ Download Dart SDK

Visit the official website:  
👉 https://dart.dev/get-dart

Follow the instructions for your operating system (Windows, macOS, or Linux).

### 2️⃣ Verify Installation

```bash
dart --version
````

---

## 🏁 Create and Run a Dart Project

```bash
dart create my_project
cd my_project
dart run
```

To run a single Dart file:

```bash
dart run filename.dart
```

---

## 🧩 Basic Example

```dart
void main() {
  print("Hello, Dart!");
}
```

---

## 📚 Dart Basics

### Variables and Data Types

```dart
var name = "Raj";
int age = 21;
double height = 5.9;
bool isStudent = true;
```

### Lists

```dart
List<int> numbers = [1, 2, 3, 4];
```

### Maps

```dart
Map<String, int> marks = {
  "Math": 90,
  "Science": 85
};
```

---

## 🔁 Control Flow

### If-Else

```dart
if (age > 18) {
  print("Adult");
} else {
  print("Minor");
}
```

### Loops

```dart
for (int i = 0; i < 5; i++) {
  print(i);
}

while (age > 0) {
  age--;
}
```

---

## 🛠️ Functions

```dart
int add(int a, int b) {
  return a + b;
}
```

Arrow function:

```dart
int square(int x) => x * x;
```

---

## 🏗️ Classes and Objects

```dart
class Person {
  String name;
  int age;

  Person(this.name, this.age);

  void greet() {
    print("Hi, I'm $name");
  }
}

void main() {
  var p = Person("Raj", 21);
  p.greet();
}
```

---

## ⚡ Asynchronous Programming

```dart
Future<String> fetchData() async {
  await Future.delayed(Duration(seconds: 2));
  return "Data loaded";
}
```

---

## 🔒 Null Safety

```dart
String? nullableName;   // Can be null
String username = "Raj"; // Cannot be null
```

---

## 📦 Package Management

Add a package:

```bash
dart pub add package_name
```

Get dependencies:

```bash
dart pub get
```

---

## 🎯 Dart with Flutter

Dart is widely used with Flutter to build:

* Android applications
* iOS applications
* Web applications
* Desktop applications

---

## 📖 Useful Links

* Official Documentation: [https://dart.dev](https://dart.dev)
* Package Repository: [https://pub.dev](https://pub.dev)
* Flutter: [https://flutter.dev](https://flutter.dev)

---

```
```
