# 📄 Advanced PDF Scanner & Document Manager

A premium, high-performance Flutter-based mobile application designed for professional document scanning, OCR (Optical Character Recognition), and PDF management. This project showcases a modern approach to mobile document processing with a focus on UI/UX excellence and robust architecture.

> [!IMPORTANT]
> **Privacy Note**: The source code for this project is currently private to prevent unauthorized distribution and to protect sensitive integration logic (API keys, security protocols, etc.). This repository serves as a portfolio piece to demonstrate the app's features, architecture, and technology stack.

---

## 🌟 Key Features

### 📸 Intelligent Scanning
- **High-Resolution Capture**: Utilizes custom camera implementations for crystal-clear document photos.
- **Auto-Cropping & Perspective Correction**: Automatically detects document edges and fixes distortions.
- **Image Enhancement**: Built-in filters (B&W, Grayscale, Magic Color) to improve document readability.

### 🔍 AI-Powered OCR
- **Text Recognition**: Extract text from images instantly using **Google ML Kit**.
- **Searchable PDFs**: Convert scanned images into text-searchable PDF documents.

### 🖋️ Digital Signatures
- **Handwritten Signatures**: Create and store multiple handwritten signatures.
- **Text Signatures**: Customizable text-based signatures with professional fonts.
- **Seamless Integration**: Place, resize, and rotate signatures anywhere on your PDF documents.

### 📂 PDF Management & Editing
- **Merge PDFs**: Combine multiple scan sessions or existing files into a single document.
- **PDF Viewer**: High-performance viewing experience powered by **Syncfusion**.
- **Page Reordering**: Easily drag and drop pages to reorganize your documents.
- **Secure Storage**: All documents are stored locally using **Hive** for lightning-fast access and offline availability.

### 🎨 Premium UI/UX
- **Neumorphic Design**: A modern, soft-UI aesthetic that provides a tactile and premium feel.
- **Dynamic Animations**: Smooth transitions and interactive elements using **Lottie**.
- **Dark/Light Mode**: Fully responsive theme support.
- 
  ### Screenshots------------------------------------------------------------------------

  home screen
  <img width="718" height="1599" alt="home" src="https://github.com/user-attachments/assets/317611d2-9ae9-485e-8d47-a6f002bb596b" />

---

## 🛠️ Technology Stack

| Category | Technology |
| :--- | :--- |
| **Framework** | Flutter (Dart) |
| **State Management** | Flutter Riverpod |
| **Navigation** | GoRouter |
| **Database** | Hive (NoSQL) |
| **Machine Learning** | Google ML Kit (Text Recognition) |
| **PDF Engine** | Syncfusion PDF / PDFx |
| **Cloud Services** | Firebase (Analytics, Crashlytics) |
| **Monetization** | AdMob & In-App Purchases |
| **Architecture** | Clean Architecture / Feature-based |

---

## 🏗️ Architecture Overview

The app follows a modern, scalable architecture designed for maintenance and testability:

- **Presentation Layer**: Built with a Neumorphic design system, utilizing Riverpod for reactive state management.
- **Domain Layer**: Contains business logic, entities, and use cases.
- **Data Layer**: Manages repositories, data sources (Hive, File System), and external service integrations.
- **Navigation**: Deep-link ready navigation system using GoRouter.

---

## 🛡️ Security & Privacy
- **Local-First**: Document processing and OCR happen on-device, ensuring user data never leaves the phone without consent.
- **No Data Leakage**: The app is built with security best practices to protect user documents.

---

## 📬 Contact & Portfolio
If you're interested in the technical implementation or would like to discuss this project, feel free to reach out.

- **Developer**: [Your Name/Github Username]
- **Project Status**: Production Ready

---
*Note: This repository is for demonstration purposes only. The full source code is under a private license.*
