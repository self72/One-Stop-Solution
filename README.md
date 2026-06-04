# Installation and Setup

## Prerequisites

Make sure the following software is installed on your system:

* Node.js (v18 or later)
* npm
* Git
* Visual Studio Code (Recommended)

---

## Clone the Repository

```bash
git clone https://github.com/self72/one-stop-solution.git
```

## Navigate to the Project Directory

```bash
cd one-stop-solution
```

## Install Dependencies

```bash
npm install
```

---

## Environment Variables

Create a `.env` file in the project root directory and add the following:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

---

## Run the Application

Start the development server:

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:5173
```

---

## Build for Production

```bash
npm run build
```

---

## Preview Production Build

```bash
npm run preview
```

---

## Running in VS Code

1. Open the project folder in Visual Studio Code.
2. Open the terminal (**Terminal → New Terminal**).
3. Run the following commands:

```bash
npm install
npm run dev
```

---

## Tech Stack

### Frontend

* React.js
* TypeScript
* Tailwind CSS
* Vite

### Backend

* Supabase

### Features

* User Authentication
* College Registration
* Event Management
* Admin Dashboard
* Responsive Design
* Secure Database Integration

This project provides a centralized platform for managing college events, registrations, and collaboration across institutions.
