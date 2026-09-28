# 🌿 BoMI: Borneo Medispa Intelligence App

**An AI-Integrated Medispa Management App**

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.13%2B-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Dart-3.0%2B-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart">
  <img src="https://img.shields.io/badge/AI-Integrated-8A2BE2?style=for-the-badge" alt="AI Integrated">
  <img src="https://img.shields.io/badge/Status-In%20Development-F5A623?style=for-the-badge" alt="Status">
</p>

<p align="center">
  <b>Smart. Simple. Intelligent.</b><br>
  A modern mobile management solution designed for Borneo Medispa.
</p>

---

## 📖 About BoMI

**BoMI** (Borneo Medispa Intelligence App) is an AI-integrated mobile application developed for **Borneo Medispa**.

The application aims to provide a centralized platform for managing medispa inventory, products, resources, and operational information while incorporating Artificial Intelligence to assist staff in making better use of available information.

BoMI combines conventional management features with an intelligent AI component to create a more efficient and user-friendly medispa management experience.

---

## 🏢 Client

**Borneo Medispa**

Borneo Medispa is a medispa and beauty-care business providing facial, skincare, pigmentation, acne-related and other beauty treatment services.

The business operates multiple locations, including locations in Sarawak such as **Kuching** and **Miri**.

| | |
|---|---|
| **Client** | Borneo Medispa |
| **Region** | Sarawak, Malaysia |
| **System** | Mobile Application |

---

## 🎯 Objectives

BoMI aims to:

- 📦 Centralize inventory and product management
- 📊 Improve visibility of stock information
- ⚠️ Assist staff in monitoring low-stock items
- 🤖 Integrate AI-powered assistance
- 🔍 Make inventory information easier to search and understand
- 📱 Provide a modern and user-friendly mobile interface
- 🔄 Reduce reliance on manual inventory management
- 🤝 Support continuous client validation throughout development

---

## ✨ Key Features

### 📦 Inventory Management

- Add new inventory items
- Update product information
- Remove inventory items
- Track stock quantities
- Categorize products
- Monitor stock status

### ⚠️ Smart Stock Monitoring

- Low-stock indicators
- Stock-level monitoring
- Restocking information
- Inventory alerts

### 🤖 AI Assistant

BoMI integrates a **cloud-based Generative AI** feature to provide intelligent assistance.

Potential functionality includes:

- Natural-language inventory queries
- AI-powered inventory insights
- Product and stock recommendations
- Inventory summaries
- Intelligent assistance for staff

**Example interaction:**

> **User:**  
> "Which products are currently low in stock?"

> **BoMI AI:**  
> "There are 4 products below the minimum stock level. Would you like to view the affected items?"

### 📊 Dashboard

The dashboard provides an overview of:

- Total inventory
- Available stock
- Low-stock items
- Product categories
- Important inventory information

### 👤 User Management

- Staff authentication
- User profiles
- Role-based access
- Secure access to system features

---

## 🧠 AI Integration

AI is one of the core components of BoMI.

The system will integrate a **cloud Generative AI API** to allow users to interact with relevant system information using natural language.

```text
┌──────────────────┐
│     BoMI App     │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│   AI Assistant   │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│ Generative AI API│
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│ AI Response /    │
│ Recommendation   │
└──────────────────┘
```

> The final AI functionality will be determined and validated based on the client's requirements.

---

## 🛠️ Technology Stack

| Category              | Technology                          |
|-----------------------|-------------------------------------|
| 📱 Frontend           | Flutter                             |
| 💻 Language           | Dart                                |
| ☁️ Backend            | Firebase / Supabase / REST API      |
| 🗄️ Database           | Cloud Database                      |
| 🤖 AI                 | Cloud Generative AI API             |
| 🔧 Version Control    | Git & GitHub                        |
| ⚙️ CI/CD              | GitHub Actions                      |
| 🧪 Testing            | Flutter Test                        |
| 🎨 UI/UX              | Flutter Material / Custom UI        |

---

## 🏗️ System Architecture

```text
┌───────────────────────────────┐
│        BoMI Mobile App        │
│           Flutter             │
└───────────────┬───────────────┘
                │
       ┌────────┴────────┐
       │                 │
       ▼                 ▼
┌─────────────┐   ┌─────────────┐
│   Backend   │   │  AI Service │
│             │   │             │
│ Firebase /  │   │ Generative  │
│ Supabase    │   │ AI API      │
└──────┬──────┘   └──────┬──────┘
       │                 │
       └────────┬────────┘
                ▼
       ┌─────────────────┐
       │    BoMI Data    │
       │   & Services    │
       └─────────────────┘
```

---

## 📱 Planned Screens

| Screen          | Description                  |
|-----------------|------------------------------|
| 🔐 Login        | User authentication          |
| 🏠 Dashboard    | Overview of system information |
| 📦 Inventory    | Manage inventory             |
| ➕ Add Item     | Add new inventory            |
| ✏️ Edit Item    | Update inventory             |
| 🤖 AI Assistant | AI-powered assistance        |
| 🔔 Notifications| Stock alerts                 |
| 👤 Profile      | User information             |

---

## 🎨 UI/UX Direction

BoMI will use a clean, modern medispa-inspired aesthetic.

**Design Principles**

- Minimalist interface
- Clean layouts
- Soft visual appearance
- Clear information hierarchy
- Consistent typography
- Intuitive navigation
- Mobile-first design
- Professional beauty & wellness aesthetic

---

## 📂 Project Structure

```text
bomi/
│
├── android/
├── ios/
├── lib/
│   │
│   ├── core/
│   │   ├── constants/
│   │   ├── theme/
│   │   └── utils/
│   │
│   ├── models/
│   │
│   ├── services/
│   │   ├── ai/
│   │   ├── auth/
│   │   └── database/
│   │
│   ├── providers/
│   │
│   ├── screens/
│   │   ├── auth/
│   │   ├── dashboard/
│   │   ├── inventory/
│   │   ├── ai/
│   │   └── profile/
│   │
│   ├── widgets/
│   │
│   └── main.dart
│
├── assets/
│   ├── images/
│   └── icons/
│
├── test/
│
├── .github/
│   └── workflows/
│
├── pubspec.yaml
├── .gitignore
└── README.md
```

---

## 🔄 Development Process

BoMI follows a structured Software Development Life Cycle (SDLC).

```text
Requirements
     ↓
System Analysis
     ↓
System Design
     ↓
Implementation
     ↓
Testing
     ↓
Client Validation
     ↓
Deployment
     ↓
Maintenance
```

Client feedback will be incorporated throughout the development process.

---

## 🧪 Testing

Testing will be performed throughout the development lifecycle.

**Testing Types**

- ✅ Unit Testing
- ✅ Widget Testing
- ✅ Integration Testing
- ✅ Functional Testing
- ✅ AI Feature Testing
- ✅ Usability Testing
- ✅ User Acceptance Testing (UAT)

The project will work towards the testing and code-coverage requirements specified by **TMA3084 Software Engineering Lab**.

---

## 🔀 GitHub Workflow

The project uses GitHub for source-code management and software engineering process tracking.

**Branch Structure**

```text
main
 │
 ├── develop
 │
 ├── feature/authentication
 ├── feature/inventory
 ├── feature/dashboard
 ├── feature/ai-assistant
 └── feature/notifications
```

**GitHub Practices**

- Issues
- Pull Requests
- Code Reviews
- Milestones
- GitHub Projects
- Feature Branches
- Commit History
- GitHub Actions
- CI/CD Pipeline

---

## 📅 Project Milestones

| Milestone | Deliverables                                      |
|-----------|---------------------------------------------------|
| 🟢 **M1** | Proposal, SRS, Team Charter & Client Validation   |
| 🟡 **M2** | SDD, Flutter Prototype & Initial AI Evidence      |
| 🟠 **M3** | Functional App, AI Integration, Testing & CI/CD   |
| 🔴 **M4** | Final App, Documentation, Demo & Client Acceptance|

---

## 👥 Team

| Member     | Role                          |
|------------|-------------------------------|
| 👤 Member 1 | Project Manager / Developer   |
| 👤 Member 2 | System Analyst / Developer    |
| 👤 Member 3 | UI/UX Designer / Developer    |
| 👤 Member 4 | AI / Backend Developer        |
| 👤 Member 5 | Testing / QA                  |

> Replace the placeholders with the actual team members and assigned roles.

---

## 🤝 Stakeholder Validation

BoMI will maintain active communication with the client throughout the project.

**Planned Validation Activities**

- 📋 Requirements discussion
- 📝 Scope confirmation
- 🎨 Prototype feedback
- 🧪 User Acceptance Testing
- 🔍 System validation
- ✍️ Final client acceptance

---

## 📸 Screenshots

| Screen | Preview |
|--------|---------|
| 🔐 Login | *Coming soon* |
| 🏠 Dashboard | *Coming soon* |
| 📦 Inventory | *Coming soon* |
| 🤖 AI Assistant | *Coming soon* |

---

## 🚀 Getting Started

### Prerequisites

Make sure the following are installed:

- Flutter 3.13+
- Dart 3.0+
- Android Studio or Visual Studio Code
- Git
- GitHub account

### Clone the Repository

```bash
git clone <repository-url>
cd bomi
```

### Install Dependencies

```bash
flutter pub get
```

### Run the Application

```bash
flutter run
```

### Run Tests

```bash
flutter test
```

---

## 🔐 Security

Sensitive information must **never** be committed to the repository.

This includes:

- API keys
- AI credentials
- Database credentials
- Authentication secrets
- Private configuration files

Use environment variables or secure configuration methods where appropriate.

---

## 📌 Project Status

<p align="center">
  <b>🚧 IN DEVELOPMENT</b><br>
  BoMI is currently under active development as part of the<br>
  <b>TMA3084 Software Engineering Lab</b> project.
</p>

---

## 🎓 Academic Information

| | |
|---|---|
| **Course** | TMA3084 Software Engineering Lab |
| **Programme** | Universiti Malaysia Sarawak (UNIMAS) |
| **Semester** | Semester 1, 2026/2027 |

This project is developed for academic purposes and follows the requirements and assessment criteria provided by the course.

---

## 📄 License

This project is developed for academic purposes as part of **TMA3084 Software Engineering Lab**.

© 2026 BoMI Development Team

---

<p align="center">
  <b>🌿 BoMI</b><br>
  Borneo Medispa Intelligence App<br>
  <i>Smart. Simple. Intelligent.</i>
</p>
