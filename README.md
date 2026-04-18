# TopSheet
Android Top Sheet equivalent To Bottom Sheet (updated code of: https://github.com/TechIsFun/AndroidTopSheet)

**How to use**

In root level `build.gradle` add following piece of code.

```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
 ``` 
  
  In app level `build.gradle` inside `dependencies` add library dependency.
  ```
  dependencies {
	        implementation 'com.github.nawinkhatiwada:TopSheet:1.0.0-alpha2'
	}
```

# 📱 TopSheet Android Demo

A modern Android sample demonstrating the implementation of a Top Sheet UI component using the TopSheet library.

---

## 🚀 Overview

This project showcases how to use a Top Sheet (similar to Bottom Sheet but from the top) to display contextual information, filters, or actions in a clean and interactive way.

---

## ✨ Features

* 🔝 Top Sheet (slide from top)
* 🎯 Smooth drag & gesture interaction
* 📱 Expand / Collapse states
* 🎨 Customizable UI
* 🌙 Supports dark mode

---

## 🛠 Dependency

```gradle id="p1k8y2"
implementation 'com.github.nawinkhatiwada:TopSheet:1.0.0-alpha2'
```

---

## 📸 Screenshots

### ⬇️ Drawer

<img width="354" height="747" alt="image" src="https://github.com/user-attachments/assets/b7d8ec97-9dac-4896-8e0c-29f455608096" />


### ⬆️ Expanded State

<img width="1004" height="726" alt="image" src="https://github.com/user-attachments/assets/c4feaf7f-fb71-4d19-905c-176f79267e53" />


### 🎮 Map Top Sheet

<img width="750" height="729" alt="image" src="https://github.com/user-attachments/assets/8ccf9054-14fe-475c-9c06-572a54ca3e00" />


### 🧰 Use Case (Filters / Menu)

<img width="899" height="479" alt="image" src="https://github.com/user-attachments/assets/66056b16-492e-4174-a62e-534f0546335d" />


---

## 💡 Use Cases

* Filter panel
* Search options
* Quick actions menu
* Media controls
* Notification preview

---

## 🔧 Implementation

```kotlin id="kotlin1"
topSheetBehavior.state = TopSheetBehavior.STATE_EXPANDED
```

---

## 🧠 What This Project Demonstrates

* Custom UI component usage
* Gesture-based interaction
* Material Design patterns
* Better UX alternatives to BottomSheet

---

## 📦 Setup

```bash id="bash1"
git clone https://github.com/Lakhvir-dev/TopSheet.git
```

---

## 👨‍💻 Author

Lakhvir Singh
Android Developer | Kotlin | Flutter

