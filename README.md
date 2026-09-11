# EduAbroad

EduAbroad — A web platform designed to help students manage their study-abroad applications and application documents. The platform connects students with an agency and its foreign partners to facilitate the management and follow-up of application files.

## 🚀 Features

* Student management
* Application file management
* Study-abroad application tracking
* Document upload and management
* Application status tracking
* Foreign partner management
* Communication between the agency and partners
* Payment management
* Payment receipt management
* Secure authentication
* Role-based access control
* Dashboard for application monitoring

### Application Workflow

The application supports different stages of an application file:

* Created
* Documents pending
* Application complete
* Sent to partner
* Received by partner
* Under review
* Additional documents requested
* Accepted
* Refused
* Closed

## 🛠️ Technologies

### Backend

* PHP
* Symfony
* API Platform
* Doctrine ORM
* PostgreSQL
* Symfony Security
* JWT Authentication

### Frontend

* React
* TypeScript
* Vite
* Axios
* HTML5
* CSS3

## 👥 Team

Developed as an academic internship project.

## 📂 Project Structure

```text
EduAbroad/
├── backend/
│   ├── config/
│   ├── migrations/
│   ├── public/
│   ├── src/
│   └── ...
│
└── frontend/
    ├── src/
    ├── public/
    ├── package.json
    └── ...
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Romaissae2004/Eduabroad.git
cd Eduabroad
```

## 2. Backend Setup

Go to the backend directory:

```bash
cd backend
```

Install the PHP dependencies:

```bash
composer install
```

Configure the PostgreSQL database connection in the `.env` file.

Example:

```env
DATABASE_URL="postgresql://username:password@127.0.0.1:5432/eduabroad"
```

Create the database:

```bash
php bin/console doctrine:database:create
```

Run the migrations:

```bash
php bin/console doctrine:migrations:migrate
```

Start the Symfony server:

```bash
symfony server:start
```

The API will be available at:

```text
https://127.0.0.1:8000
```

## 3. Frontend Setup

Open a new terminal and go to the frontend directory:

```bash
cd frontend
```

Install the required dependencies:

```bash
npm install
```

Start the React application:

```bash
npm run dev
```

The frontend will be available at:

```text
http://localhost:5173
```

## 4. Database

EduAbroad uses PostgreSQL as its database.

Create a PostgreSQL database and configure the database connection in the backend `.env` file before running the application.

## 📌 Project Purpose

EduAbroad aims to simplify the management and monitoring of students' study-abroad application files. It provides a centralized platform for managing students, documents, application statuses, partners, payments, and receipts throughout the application process.
