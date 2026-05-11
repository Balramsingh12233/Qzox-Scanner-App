# 📄 Advanced PDF Scanner & Document Manager

A premium, high-performance Flutter-based mobile application designed for professional document scanning, OCR (Optical Character Recognition), and PDF management. This project showcases a modern approach to mobile document processing with a focus on UI/UX excellence and robust architecture.

> [!IMPORTANT]
> **Privacy Note**: The source code for this project is currently private to prevent unauthorized distribution and to protect sensitive integration logic (API keys, security protocols, etc.). This repository serves as a portfolio piece to demonstrate the app's features, architecture, and technology stack.
>
>
>  Get Source Code: (https://www.codester.com/items/65126/qzox-scanner-premium-neumorphic-document-scanner?ref=balramsingh)

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
  ### We provide some Screenshots ------------------------------------------------------------------------

  home screen
  <img width="718" height="1599" alt="home" src="https://github.com/user-attachments/assets/317611d2-9ae9-485e-8d47-a6f002bb596b" />

  Id Photo Editor Screen
  <img width="718" height="1599" alt="WhatsApp Image 2026-04-24 at 11 29 38 PM" src="https://github.com/user-attachments/assets/4635067d-b038-45c7-8262-f1d7577f6944" />

  Resize Any Photo/Custom Id Photo Editor Screen
  <img width="718" height="1599" alt="WhatsApp Image 2026-04-28 at 5 20 33 PM (2)" src="https://github.com/user-attachments/assets/1dacc1cd-9c62-4697-b312-2077f53e6e10" />

  Premium Plan
  <img width="718" height="1599" alt="premium" src="https://github.com/user-attachments/assets/afdef095-cd38-4aa1-8487-ded0c62db71f" />

  
  Pending Task
  <img width="718" height="1599" alt="WhatsApp Image 2026-04-28 at 5 22 26 PM (1)" src="https://github.com/user-attachments/assets/cad6f85b-0297-4a44-8487-004b6826d24d" />

  Save Pdfs
  <img width="718" height="1599" alt="WhatsApp Image 2026-04-28 at 12 00 40 PM (1)" src="https://github.com/user-attachments/assets/8ec1bb0d-26da-4725-87fa-7044887e55b9" />


 Add Sign On the Pdf Documents
 <img width="718" height="1599" alt="WhatsApp Image 2026-04-24 at 11 02 36 PM" src="https://github.com/user-attachments/assets/7c72f220-f566-485c-acac-35b3d84cc0d7" />

 Ocr History
 <img width="720" height="1604" alt="WhatsApp Image 2026-04-28 at 12 00 38 PM" src="https://github.com/user-attachments/assets/f21e117a-49f1-476c-b943-2834d68b62c4" />

 Select files that You want to convert imaGES into PDFs, merge PDFs, split PDFs
 <img width="720" height="1604" alt="WhatsApp Image 2026-04-28 at 12 00 38 PM (1)" src="https://github.com/user-attachments/assets/90d11d30-4309-4cfc-b046-2938c96b679b" />

 Set Expiry Alert On Documents
 <img width="720" height="1604" alt="WhatsApp Image 2026-05-05 at 11 53 35 AM" src="https://github.com/user-attachments/assets/642edc6a-692b-407c-a304-4929522bc08e" />

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
- **Email: balramsingh12233@gmail.com
- **Developer**: [Balram Tech Hub]
- **Project Status**: Production Ready
- ** App Link: https://play.google.com/store/apps/details?id=com.qzox.pdfscanner&hl=en

---
*Note: This repository is for demonstration purposes only. The full source code is under a private license.*
