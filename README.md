# 🚀 Dev Stack Builder

> **Explore technologies. Build your stack. Choose the tools for your development journey.**

[![Live Website](https://img.shields.io/badge/Live%20Website-dev--stack.openyhool.com-blue?style=for-the-badge)](https://dev-stack.openyhool.com/)
[![GitHub](https://img.shields.io/badge/GitHub-Rumi--Parvez-181717?style=for-the-badge\&logo=github)](https://github.com/Rumi-Parvez/DevStack)

---

## 📌 Project Overview

**Dev Stack Builder** is a modern interactive web application built for developers and programming learners who want to explore different development technologies and create their own personalized technology stack.

The application displays technology information through interactive cards and allows users to add technologies to their personal stack, manage selected technologies, and receive feedback through interactive notifications.

The project focuses on practicing modern **React, TypeScript, Tailwind CSS, responsive design, component-based architecture, state management, and dynamic data handling**.

---

## 🌐 Live Project

🚀 **Live Website:**
https://dev-stack.openyhool.com/

💻 **GitHub Repository:**
https://github.com/Rumi-Parvez/DevStack

---

<p align="center">
  <img 
    src="https://i.postimg.cc/GhyNb3Df/3.png" 
    alt="Dev Stack Builder Project Cover" 
    width="100%" 
  />
</p>
---

# ✨ Main Features

### 📚 Technology Exploration

Browse a collection of development technologies and explore their information through interactive cards.

### 🔎 Technology Details

Each technology can provide information such as:

* Technology name
* Category
* Description
* Rating
* Difficulty level
* Badge
* Technology icon

### ➕ Add to Stack

Users can add technologies they are interested in to their personal development stack.

### 🚫 Duplicate Prevention

The same technology cannot be added multiple times.

### 🔒 Disabled Selected State

After a technology has been added, its **Add to Stack** action becomes disabled to clearly indicate that it is already selected.

### 🗑️ Remove Technology

Users can remove individual technologies from their selected stack.

### 🧹 Remove All

Users can clear all selected technologies from the stack.

### 🔢 Stack Counter

The application displays the number of technologies currently selected.

### 🔔 Toast Notifications

Interactive actions provide feedback using **React Toastify** notifications.

### ⏳ Loading State

A loading state is displayed while technology data is being loaded.

### 📱 Responsive Design

The interface is designed to work across:

* Desktop
* Tablet
* Mobile

### ⚡ Interactive UI

The interface dynamically updates based on user actions without requiring a page reload.

---

# 🛠️ Main Technologies

| Technology            | Usage                                   |
| --------------------- | --------------------------------------- |
| ⚛️ **React**          | Building the interactive user interface |
| 📘 **TypeScript**     | Type-safe application development       |
| 🎨 **Tailwind CSS**   | Styling and responsive layouts          |
| 🌼 **DaisyUI**        | UI components and design utilities      |
| ⚡ **Vite**            | Development server and build tooling    |
| 🔔 **React Toastify** | Toast notifications                     |
| 🧩 **React Icons**    | Icons throughout the interface          |
| 📦 **JSON**           | Structured technology data              |
| 🧱 **HTML5**          | Application structure                   |
| 🎨 **CSS3**           | Styling and layout                      |

---

# 🧠 Concepts Practiced

This project was built as a practical frontend development project to apply modern development concepts.

## ⚛️ React

* Functional Components
* Props
* State Management
* Event Handling
* Conditional Rendering
* List Rendering
* Reusable Components
* Component Composition
* Dynamic UI Updates
* Data Loading

## 📘 TypeScript

* Interfaces
* Type Definitions
* Typed Props
* Typed State
* Type-safe data handling
* Type-safe component development

## 🎨 Styling

* Tailwind CSS
* DaisyUI
* Responsive Design
* Flexbox
* Grid Layout
* Responsive Components
* Interactive States

## 📊 Data Handling

* JSON data
* Asynchronous data loading
* Loading states
* Array methods
* Dynamic rendering
* Data filtering
* Technology data management

---

# 🔄 Main User Flow

The application's main workflow is:

```text
Explore Technologies
        ↓
View Technology Information
        ↓
Choose a Technology
        ↓
Add to Stack
        ↓
View Selected Stack
        ↓
Manage Selected Technologies
        ↓
Remove One / Remove All
```

---

# 📊 Technology Data

The application uses structured technology data to dynamically generate the technology cards.

A technology object can contain information such as:

```json
{
  "id": 1,
  "name": "React",
  "category": "Frontend",
  "description": "A JavaScript library for building user interfaces.",
  "icon": "...",
  "rating": 9.5,
  "difficulty": "Intermediate",
  "badge": "Popular"
}
```

Using structured data makes the application easier to maintain and allows the UI to render technologies dynamically.

---

# 🎨 UI & UX

The project focuses on creating a clean and developer-friendly interface.

### UI considerations include:

* Clear navigation
* Responsive layouts
* Technology-focused cards
* Consistent spacing
* Clear typography
* Interactive buttons
* Disabled button states
* Loading feedback
* Toast notifications
* Stack management
* Responsive navigation

The goal is to provide a simple experience where users can understand the application and start building their stack quickly.

---

# 📱 Responsive Design

The application adapts to different screen sizes:

```text
Desktop
   ↓
Tablet
   ↓
Mobile
```

Responsive behavior is applied to the application's:

* Navigation
* Technology cards
* Layout
* Spacing
* Buttons
* Stack section
* Content areas

---

# 📂 Project Structure

The project follows a component-based React structure.

```text
DevStack/
│
├── public/
│
├── src/
│   ├── assets/
│   │
│   ├── components/
│   │
│   ├── data/
│   │
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
│
├── .gitignore
├── .oxlintrc.json
├── index.html
├── package.json
├── package-lock.json
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
├── vite.config.ts
└── README.md
```

The repository currently contains the main `public`, `src`, Vite, TypeScript, package, and configuration files used to run the application.

---

# 📦 Dependencies

## Main Dependencies

```text
react
react-dom
react-icons
react-toastify
```

## Development Dependencies

```text
typescript
vite
tailwindcss
daisyui
@tailwindcss/vite
@vitejs/plugin-react
@types/react
@types/react-dom
@types/node
oxlint
```

> The exact dependency versions are available in the project's `package.json` and `package-lock.json`.

---

# 💻 Run the Project Locally

Follow these steps to run **Dev Stack Builder** on your local machine.

## 1. Clone the Repository

```bash
git clone https://github.com/Rumi-Parvez/DevStack.git
```

## 2. Go to the Project Directory

```bash
cd DevStack
```

## 3. Install Dependencies

```bash
npm install
```

## 4. Start the Development Server

```bash
npm run dev
```

After starting the development server, open the local URL provided by Vite in your browser.

Usually:

```text
http://localhost:5173
```

---

# 📦 Production Build

To create a production-ready build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

---

# 🧹 Code Quality

The project also includes **Oxlint** for code-quality checking.

Run:

```bash
npm run lint
```

This helps identify potential code-quality and linting issues during development.

---

# 🔮 Future Improvements

Possible future improvements for the project include:

* 🔍 Technology Search
* 🏷️ Category Filtering
* ⭐ Rating-based Filtering
* 📊 Technology Comparison
* 💾 Persistent Stack Storage
* 🔐 User Authentication
* 👤 Developer Profiles
* 🌙 Dark Mode
* 📈 Stack Statistics
* 🔗 Shareable Developer Stacks
* ☁️ Backend Integration
* 🗄️ Database Integration
* 📱 Progressive Web App Support

---

# 🎯 Project Goals

The main goals of this project are to:

* Practice modern React development
* Apply TypeScript in a real project
* Build reusable components
* Practice state management
* Work with structured data
* Create responsive interfaces
* Improve UI/UX development skills
* Build an interactive real-world style application

---

# 👨‍💻 Developer

## Rumi Parvez

**Full-Stack Developer & Software Engineer**

I am passionate about building modern, responsive, and user-focused web applications while continuously learning new technologies and improving my development skills.

This project represents practical experience with **React, TypeScript, Tailwind CSS, component architecture, state management, data handling, responsive design, and interactive UI development**.

### GitHub

https://github.com/Rumi-Parvez

---

# 🔗 Relevant Links

| Resource                   | Link                                    |
| -------------------------- | --------------------------------------- |
| 🚀 **Live Website**        | https://dev-stack.openyhool.com/        |
| 💻 **GitHub Repository**   | https://github.com/Rumi-Parvez/DevStack |
| 👨‍💻 **Developer GitHub** | https://github.com/Rumi-Parvez          |

---

# ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.

You can also fork the repository and explore the source code.

---

# 🚀 Build Your Stack. Build Your Future.

**Dev Stack Builder** is an interactive technology exploration application that helps developers and learners discover technologies and organize their preferred tools into a personalized development stack.

**Made with ❤️ by Rumi Parvez**
