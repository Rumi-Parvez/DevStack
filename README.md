# 🚀 Dev Stack Builder

> **Build your development stack. Explore technologies. Choose your tools.**

🌐 **Live Website:** https://dev-stack.openyhool.com/

**Dev Stack Builder** is an interactive web application that allows developers and learners to explore different development technologies and create their own personalized technology stack.

Users can browse technologies, learn about them through detailed cards, and add their preferred technologies to their personal stack.

---

## ✨ Features

* 📚 Browse a collection of development technologies
* 🔎 Explore technology information through interactive cards
* ➕ Add technologies to your personal stack
* 🚫 Prevent duplicate technologies
* 🔒 Disable the **Add to Stack** button for already-selected technologies
* 🗑️ Remove individual technologies
* 🧹 Remove all technologies from the stack
* 🔢 Display the number of selected technologies
* 🔔 Toast notifications for user actions
* ⏳ Loading state while fetching technology data
* 📱 Fully responsive design
* 🎨 Modern and clean user interface
* ⚡ Fast and interactive user experience

---

## 🖥️ Live Demo

Visit the live application:

👉 **https://dev-stack.openyhool.com/**

---

## 🛠️ Technologies Used

| Technology          | Purpose                                       |
| ------------------- | --------------------------------------------- |
| ⚛️ React            | Building the user interface                   |
| 📘 TypeScript       | Type safety and better development experience |
| 🎨 Tailwind CSS     | Styling and responsive design                 |
| 🌼 DaisyUI          | UI components                                 |
| ⚡ Vite              | Development and build tooling                 |
| 🟨 JavaScript / ES6 | Application logic                             |
| 🧱 HTML5            | Page structure                                |
| 🎨 CSS3             | Styling fundamentals                          |
| 📦 JSON             | Technology data                               |
| 🔔 React Toastify   | User notifications                            |

---

## 🧠 What I Practiced

This project was built as a practical frontend development project to apply modern React and TypeScript concepts.

### React

* Components
* Props
* State management
* Event handling
* Conditional rendering
* List rendering
* Reusable components
* Data loading

### TypeScript

* Interfaces
* Type definitions
* Typed props
* Typed state
* Typed API/data responses
* Type-safe component development

### Data Handling

* External JSON data
* Asynchronous data fetching
* Loading states
* Data filtering
* Array methods
* Dynamic rendering

### User Interaction

The application provides an interactive stack-building experience.

Users can:

```text
Explore Technology
       ↓
Select Technology
       ↓
Add to Stack
       ↓
View Selected Stack
       ↓
Remove / Manage Technologies
```

---

## 📂 Project Structure

```text
src/
├── assets/
│   └── images/
│
├── components/
│   ├── Navbar/
│   ├── Hero/
│   ├── TechnologyCard/
│   ├── TechnologyList/
│   ├── Stack/
│   └── Footer/
│
├── data/
│   └── technologies.json
│
├── pages/
│
├── App.tsx
├── main.tsx
└── index.css
```

> The exact structure may vary depending on the final project organization.

---

## 🎯 Main User Flow

### 1. Explore Technologies

Users can browse different technologies and see information such as:

* Technology name
* Category
* Description
* Rating
* Difficulty
* Badge
* Icon

### 2. Add to Stack

When a user finds a technology they want to use, they can add it to their personal stack.

### 3. Duplicate Protection

A technology cannot be added multiple times.

Once a technology has been added, its button becomes disabled to make the state clear to the user.

### 4. Manage Stack

Users can manage their selected technologies by:

* Removing one technology
* Removing all technologies

---

## 📱 Responsive Design

The application is designed to provide a consistent experience across different screen sizes.

```text
Desktop
   ↓
Tablet
   ↓
Mobile
```

The interface adapts its layout, spacing, cards, navigation, and content according to the available screen size.

---

## 🎨 UI & UX

The project focuses on creating a simple and developer-friendly experience.

Important UI/UX considerations include:

* Clear navigation
* Responsive layouts
* Consistent spacing
* Technology-focused cards
* Visible interaction states
* Disabled states
* Loading feedback
* Toast notifications
* Clear stack management

The goal is to make the application easy to understand even for someone visiting it for the first time.

---

## 📊 Technology Data

The application uses structured technology data containing information such as:

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

This makes the application easier to maintain and allows the UI to be generated dynamically from the data.

---

## ⚡ Getting Started

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Move into the project directory:

```bash
cd dev-stack
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Then open the local development URL provided by Vite.

---

## 📦 Build for Production

Create a production build:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

## 🔮 Future Improvements

Possible future improvements include:

* 🔍 Technology search
* 🏷️ Category filtering
* ⭐ Rating-based filtering
* 📊 Technology comparison
* 💾 Persistent stack storage
* 🔐 User authentication
* 👤 Personal developer profiles
* 🌙 Dark mode
* 📈 Stack statistics
* 🔗 Shareable developer stacks
* ☁️ Backend integration
* 🗄️ Database support

---

## 👨‍💻 Developer

### Rumi Parvez

Frontend Developer & Programming Learner

This project was created as a practical development project to apply React, TypeScript, Tailwind CSS, and modern frontend development concepts in a real-world style application.

The project represents hands-on practice with component architecture, state management, data handling, responsive UI development, and user interaction.

---

## 🌐 Project Links

| Resource        | Link                             |
| --------------- | -------------------------------- |
| 🚀 Live Website | https://dev-stack.openyhool.com/ |
| 💻 GitHub       | YOUR_GITHUB_REPOSITORY           |
| 📚 Project      | Dev Stack Builder                |

---

## ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.

---

# 🚀 Build Your Stack. Build Your Future.

**Dev Stack Builder** is more than a technology list — it is a small interactive environment for discovering, selecting, and organizing the technologies that make up a modern developer's toolkit.

**Made with ❤️ by Rumi Parvez**
