# SEEN — Diabetes Care & Community App

![SEEN Demo](demo/Seen_demo.gif)

**SEEN** is a diabetes care and community Android application developed as a **graduation project**. The app helps users track their diabetes-related health data, manage medications and meals, interact with a community, and access an AI-powered diabetes care assistant.

The Android application is built with **Kotlin and XML** using a structured **MVVM architecture**.

---

## 📱 Project Overview

SEEN provides users with a centralized mobile platform for managing their diabetes-related information and daily activities.

The application focuses on:

* Blood glucose tracking
* Medication management
* Meal logging
* Personalized reminders
* Health reports
* Community interaction
* AI-powered diabetes assistance
* Arabic and English support

---

## 🚀 Features

### 🔐 Authentication

* User registration and login
* Secure authentication
* User profile management
* Personalized health information

### 🩸 Glucose Tracking

* Record blood glucose readings
* Specify reading type, such as before or after meals
* Add notes to glucose readings
* View previous readings
* Track glucose history

### 💊 Medication Management

* Add and manage medications
* Record medications taken
* Track medication history
* Set medication reminders

### 🍽️ Meal Tracking

* Record meals and meal types
* Add meal descriptions
* Track estimated carbohydrates and calories
* Add notes related to meals

### 📊 Reports

Users can view reports and summaries of their recorded health data to better understand their diabetes-related patterns.

### ⏰ Reminders

* Medication reminders
* Scheduled health-related reminders
* View upcoming reminders

### 👥 Community

SEEN includes a community section where users can:

* Create posts
* Share experiences
* Interact with other users
* View diabetes-related content

### 🤖 AI Diabetes Care Assistant

SEEN includes an AI-powered diabetes care assistant that allows users to ask diabetes-related questions through a conversational interface.

The assistant supports:

* Arabic and English conversations
* Diabetes-related questions
* Personalized responses based on available user context
* Medical knowledge retrieval
* Source-based responses

---

## 🧠 AI Assistant

The AI assistant uses a **Retrieval-Augmented Generation (RAG)** approach to provide responses grounded in a collection of medical documents.

From the Android application, users can interact with the assistant through a conversational chat interface.

The application sends the user's question and relevant context to the AI service and displays the generated response and available sources.

---

## 🏗️ Android Architecture

The Android application follows the **MVVM (Model–View–ViewModel)** architecture.

```text
UI / Fragments
      ↓
   ViewModel
      ↓
  Repository
      ↓
  Remote / Local Data
      ↓
    API / Room
```

### Architecture Components

* **MVVM** for separation of concerns
* **Repository Pattern** for centralized data access
* **ViewModel** for managing UI-related state
* **Retrofit** for API communication
* **Room** for local data persistence
* **Resource states** for handling Loading, Success, and Error states
* **Pagination** for efficiently loading larger datasets
* **Internet connectivity checks**
* Centralized API error handling

---

## 🛠️ Tech Stack

### Android

* **Kotlin**
* **XML**
* **Android SDK**
* **MVVM**
* **Repository Pattern**
* **Retrofit**
* **OkHttp**
* **Room**
* **Coroutines**
* **Pagination**
* **Material Components**

### AI Integration

* REST API communication
* RAG-based AI assistant
* Arabic/English language support
* Medical knowledge retrieval

---

## 📱 Android Development Highlights

The project demonstrates practical Android development concepts including:

* Multi-screen application development
* MVVM architecture
* Repository-based data management
* REST API integration
* Local database management with Room
* Authentication and user sessions
* Paginated data loading
* Network state handling
* Form validation
* Health data visualization
* Conversational AI integration
* Arabic-first user experience

---

## 🎓 Graduation Project

SEEN was developed as a **graduation project**, combining Android application development with healthcare-focused features and AI integration.

The project demonstrates the development of a complete Android application with a focus on **clean architecture, maintainable code, API integration, local data management, and AI-powered user interaction**.

---

## ⚠️ Disclaimer

SEEN is an educational graduation project and is **not intended to provide medical diagnosis or replace professional medical advice**.

The AI assistant provides informational responses and should not be used as a substitute for consultation with a qualified healthcare professional.