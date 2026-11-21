
# Smart Enquiry Management System

An AI-powered enquiry management platform designed to help businesses collect, organize, analyze, and manage client enquiries through a centralized system.

The system integrates chatbot-based enquiry collection, email workflows, and manually recorded enquiries to streamline enquiry handling and improve follow-up management.

## Overview

Businesses often receive enquiries through multiple channels, making it difficult to track client requirements, maintain records, and ensure timely follow-ups.

The Smart Enquiry Management System provides a centralized platform to manage enquiries from different sources while using AI to understand client requirements and assist in enquiry processing.

## Key Features

### 🤖 AI-Powered Chatbot – Eva
- Conversational interface for collecting client enquiries.
- Collects client information such as name, email, phone number, company, and requirements.
- Understands natural-language responses.
- Identifies missing information and asks relevant follow-up questions.
- Analyzes and structures client requirements.
- Collects user confirmation before submitting the enquiry.

### 📧 Email-Based Enquiry Management
- Supports email-based enquiry workflows.
- Helps process and manage enquiries received through email.
- Integrates email workflows with the enquiry management system.

### 📋 Centralized Enquiry Management
- Stores enquiries from different channels in a centralized system.
- Enables viewing and managing enquiry records.
- Supports enquiry status tracking and management.

### 📊 Dashboard & Tracking
- Provides an overview of enquiry information.
- Helps monitor enquiry records and their statuses.
- Supports organized enquiry management.

### 👥 Client Management
- Maintains client-related information associated with enquiries.
- Helps organize client records and enquiry history.

---

## System Architecture

The application follows a frontend-backend architecture.

**Frontend**
- React.js
- JavaScript
- Bootstrap

**Backend**
- Python
- Flask
- Flask Blueprints
- SQLAlchemy

**Database**
- SQLite

**AI Integration**
- Groq API
- Llama 3.3 70B Versatile

**Email Integration**
- IMAP / SMTP

---

## Workflow

```text
Client Enquiry
      │
      ▼
 ┌─────────────────────┐
 │   Enquiry Sources  │
 └─────────────────────┘
      │
 ┌────┼──────────────┐
 ▼    ▼              ▼
Chatbot  Email   Manual Entry
 │        │          │
 └────────┼──────────┘
          ▼
  Central Enquiry System
          │
          ▼
  AI Requirement Analysis
          │
          ▼
 Enquiry Record Management
          │
          ▼
 Status Tracking & Follow-up
```

---

## Technology Stack

| Component | Technologies |
|---|---|
| Frontend | React.js, JavaScript, Bootstrap |
| Backend | Python, Flask |
| API Architecture | Flask Blueprints |
| ORM | SQLAlchemy |
| Database | SQLite |
| AI | Groq API, Llama 3.3 70B Versatile |
| Email | IMAP, SMTP |
| Version Control | Git, GitHub |

---

## Project Structure

```text
Enquiry-Portal-Fixed-/
│
├── poc/
│   ├── backend/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── models/
│   │   └── ...
│   │
│   └── frontend/
│       ├── src/
│       │   ├── components/
│       │   ├── pages/
│       │   └── ...
│       └── ...
│
└── package-lock.json
```

---

## Getting Started

### Prerequisites

- Python 3.10+
- Node.js and npm
- Git
- Groq API key

### 1. Clone the Repository

```bash
git clone https://github.com/nabihaa/Enquiry-Portal-Fixed-.git
cd Enquiry-Portal-Fixed-
```

### 2. Backend Setup

Navigate to the backend directory:

```bash
cd poc/backend
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure the required environment variables in your `.env` file.

Start the backend server using the project's Flask entry point.

### 3. Frontend Setup

Open another terminal and navigate to:

```bash
cd poc/frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

> The exact startup commands may vary depending on the project's configured scripts and entry points.

---

## Environment Configuration

Create a `.env` file for configuration values such as API keys, email credentials, and application settings.

Example:

```env
GROQ_API_KEY=your_groq_api_key
```

**Do not commit API keys, passwords, email credentials, or other secrets to GitHub.**

---


Both contributors collaborated on the Smart Enquiry Management System.

---

## Future Enhancements

- Deployment to a cloud environment.
- Integration with additional communication channels.
- Advanced enquiry prioritization.
- Improved analytics and reporting.
- Automated follow-up recommendations.
- Enhanced AI-based enquiry classification.
- Scalable database integration.

---

## Project Information

**Project:** Smart Enquiry Management System  
**Organization:** Oraiyan Innovations  
**Project Type:** Internship Project  
**Domain:** Full Stack Development, Artificial Intelligence

---

## Acknowledgements

We would like to thank Oraiyan Innovations for providing us with the opportunity to work on this project as part of our internship and for their guidance throughout the development process.

---

⭐ If you find this project interesting, feel free to explore the repository.
