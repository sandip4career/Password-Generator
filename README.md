# 🔐 Password Generator

A simple and responsive **Password Generator** built with **React.js**.
It allows users to generate secure passwords by choosing the password length and whether to include numbers and special characters.

## 🚀 Features

* Generate random passwords
* Adjustable password length
* Include/exclude numbers
* Include/exclude special characters
* Copy generated password to clipboard
* Responsive user interface
* Built using React Hooks

## 🛠️ Technologies Used

* React.js
* JavaScript (ES6+)
* HTML5
* CSS3
* React Hooks

  * `useState`
  * `useCallback`
  * `useEffect`
  * `useRef`

## 📂 Project Structure

```text
passwordGenerator/
├── public/
├── src/
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .gitignore
├── package.json
└── README.md
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/sandip4career/Password-Generator.git
```

Go to the project directory:

```bash
cd Password-Generator
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL shown in your terminal, usually:

```text
http://localhost:5173
```

## 💡 How It Works

The application uses React state to manage:

* Password length
* Number inclusion
* Special-character inclusion
* Generated password

React's `useCallback` is used to optimize the password generation function, while `useRef` is used to access the generated password for copying.

## 📸 Preview

You can add a screenshot of the application here:

```markdown
![Password Generator](./screenshots/password-generator.png)
```

## 🎯 Learning Goals

This project was created to practice:

* React functional components
* React Hooks
* State management
* Event handling
* Conditional logic
* Random password generation
* Clipboard API
* Git and GitHub

## 🔮 Future Improvements

* Password strength indicator
* Custom character selection
* Password history
* Dark/light mode
* Improved accessibility

## 👨‍💻 Author

**Sandip Yadav**

* GitHub: https://github.com/sandip4career
* LinkedIn: https://linkedin.com/in/sandip4career/

---

⭐ If you find this project useful, consider giving it a star!
