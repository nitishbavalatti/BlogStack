# 📝 BlogCraft - Flask Blog Application

A dynamic and responsive blogging platform built using Flask. This application allows users to register, log in, create posts, and interact through comments with a clean UI.

---

## 🚀 Features

* 🔐 User Authentication (Register/Login/Logout)
* ✍️ Create, Edit, and Delete Blog Posts
* 💬 Comment System on Posts
* 🖼️ Image Support via URL
* 🧠 Rich Text Editor (CKEditor)
* 👤 User-based Access Control (Admin features)
* 🎨 Clean UI using Bootstrap

---

## 🛠️ Tech Stack

* **Backend:** Flask (Python)
* **Database:** SQLite (SQLAlchemy)
* **Authentication:** Flask-Login
* **Forms:** Flask-WTF
* **Editor:** Flask-CKEditor
* **Frontend:** HTML, CSS, Bootstrap

---

## 📂 Project Structure

```bash
BLOG_POST/
│── main.py
│── forms.py
│── requirements.txt
│── .gitignore
│
├── templates/
│   ├── about.html
│   ├── contact.html
│   ├── footer.html
│   ├── header.html
│   ├── index.html
│   ├── login.html
│   ├── make-post.html
│   ├── post.html
│   └── register.html
│
├── static/
│   └── css/
│       └── styles.css
│
├── instance/        # Database files (ignored)
├── .venv/           # Virtual environment (ignored)
└── __pycache__/     # Python cache (ignored)
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/BlogCraft.git
cd BlogCraft
```

### 2. Create virtual environment

```bash
python -m venv .venv
.venv\Scripts\activate      # Windows
# source .venv/bin/activate  # Mac/Linux
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the app

```bash
python main.py
```

---

## 🌐 Usage

* Register a new account
* Login to access features
* Create and manage blog posts
* Comment on posts
* Admin (User ID = 1) can delete/edit posts

---

## 🔒 Important Notes

* `.venv`, `instance/`, and `__pycache__/` are ignored using `.gitignore`
* Database file (`posts.db`) is not uploaded for security and portability

---

## 📌 Future Improvements

* 🔎 Search functionality
* ❤️ Like/Bookmark posts
* 🌍 Deploy to cloud (Render / Railway)
* 📊 Admin dashboard

---

## 👨‍💻 Author

**Nitish RB**

---
