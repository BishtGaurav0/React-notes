# 📚 React Notes App – Understanding React & Web Concepts

## 📌 Introduction
This simple React application is designed to provide quick reference notes for developers learning **React** and general **web development concepts**. The app includes essential comparisons like **Library vs Framework**, as well as an explanation of key files and folder structures used in React projects. It serves as a learning and revision tool for beginners and intermediates alike.

## 🧩 Project Type
🎨 Frontend (Learning Tool)

## 🌐 Deployed App  
🔗 Live App: [https://youthful-liskov-7d0379.netlify.app/](https://youthful-liskov-7d0379.netlify.app/)  


## 📁 Directory Structure
react-notes/ ├─ public/ │ └─ index.html ├─ src/ │ ├─ App.js │ └─ index.js ├─ .gitignore ├─ package.json ├─ package-lock.json └─ README.md

## 🎥 Video Walkthrough of the Project  
<p align="center">
  <a href="https://drive.google.com/file/d/1dcB0HOdTlS9f1vCX_vQPem_Flj6KocNM/view">
    <img src="https://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg" alt="Watch the walkthrough video" width="600">
  </a>
</p>


---

## 📘 Notes Included

### 🧠 Library vs Framework

- 📦 **Library** is a collection of functions.
- 🏗️ **Framework** is a collection of multiple other libraries.
- 🔁 **Inversion of Control**:
  - With a **library**, the execution flow is controlled by the **developer**.
  - With a **framework**, the **framework controls** the flow, and developers plug into it.
- ⚙️ **Frameworks** usually follow an **MVC (Model-View-Controller)** structure.
  - A **library** like **React** only handles the **View** part.
- 📐 **Frameworks** provide a predefined structure where developers implement functionality.
  - With libraries, developers must define their own structure.

---

### 📂 React Folder Structure Explained

#### 📄 `README.md`
- Contains information about the project, its structure, and developer guidelines.

#### 📦 `package.json`
- Describes the project configuration.
- Lists dependencies (libraries used in the project).
- Contains scripts (commands like `start`, `build`, `test`, etc.)

#### 📦 `package-lock.json`
- Records the full dependency tree.
- Includes information about every installed package and their nested dependencies.

#### 🛑 `.gitignore`
- Specifies files and folders to be **ignored** by Git.
- Commonly includes `node_modules/`, build files, and environment files.

#### 🧾 `public/index.html`
- Contains a single `<div>` element with an `id`, where the entire React app is rendered.

#### ⚛️ `src/index.js`
- The **entry point** of the application.
- Renders the React app into the root element found in `index.html`.

#### 📁 `src/App.js`
- The **main component** where developers begin building their React application.
- Acts as the root component that connects other components and logic.

---

## 🛠️ Installation & Getting Started

```bash
git clone https://github.com/yourusername/react-notes.git
cd react-notes
npm install
npm start
