# Blog CI Demo 📝🚀

This is a simple blog application built with **Node.js**, **Express**, **EJS**, and **MySQL** — created primarily to demonstrate **Continuous Integration (CI)** using **GitHub Actions**.

---

## 🧰 Tech Stack

- Node.js
- Express.js
- EJS (Embedded JavaScript Templates)
- MySQL
- GitHub Actions (CI)

---

## 📁 Folder Structure

```
Blog-CI-Demo/
├── .github/workflows/       # GitHub Actions CI workflow
├── views/                   # EJS templates
├── index.js                 # Entry point of the app
├── package.json             # Project metadata and dependencies
└── ...
```

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ptlvaibhav/Blog-CI-Demo.git
cd Blog-CI-Demo
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up MySQL

Create a MySQL database named `blogdb` and configure your environment:

Create a `.env` file (if not already):

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=blogdb
PORT=3000
```

> Or edit the hardcoded variables in `index.js` if `.env` is not used.

### 4. Run the App

```bash
npm run dev
```

Visit: `http://localhost:3000`

---

## 🤖 GitHub Actions CI

This repository includes a CI pipeline using GitHub Actions.

- Location: `.github/workflows/node.js.yml`
- Tasks:
  - Installs dependencies
  - Runs tests (if added)
  - Lints code
  - Builds (if applicable)

---

## 📜 License

This repository is intended for **educational and demonstration purposes only**.

---

## 🙋‍♂️ Author

Created and maintained by [@ptlvaibhav](https://github.com/ptlvaibhav)
