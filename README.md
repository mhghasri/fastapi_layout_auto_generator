# fastapi_layout_auto_generator


# FastAPI Layout Auto Generator 🚀

A simple and lightweight CLI tool to scaffold FastAPI projects and apps,
inspired by Django's `startapp` command.

This tool helps you quickly generate a clean, opinionated FastAPI app layout
without repeating boilerplate code.

---

## ✨ Features

- ✅ Create FastAPI apps with a single command
- ✅ Django-like `startapp` experience
- ✅ Clean and readable project structure
- ✅ No external dependencies
- ✅ Pure Bash – fast and simple
- ✅ Easy to customize and extend

---

## 📁 Generated App Structure

When you run:
```bash
start-fastapi startapp users
```

The following structure will be created:

users/
├── __init__.py
├── models.py
├── schemas.py
├── routers.py
├── services.py
└── tests.py

Each file is pre-filled with useful imports and comments.

🛠 Installation
1️⃣ Clone the repository
https://github.com/mhghasri/fastapi_layout_auto_generator.git

2️⃣ Make scripts executable
bash
chmod +x start-fastapi fastapi-app
3️⃣ Add scripts to your PATH
bash
mkdir -p ~/bin
mv start-fastapi fastapi-app ~/bin
Add this line to your ~/.profile (recommended):

bash
export PATH="$HOME/bin:$PATH"
Then reload your shell:

bash
source ~/.profile
🚀 Usage
Create a new FastAPI app
bash
start-fastapi startapp users
✅ This will create a users/ directory with all required files.

📄 File Contents Overview
models.py
Includes SQLAlchemy base imports and a placeholder for model classes.

schemas.py
Includes Pydantic BaseModel and EmailStr.

routers.py
Preconfigured with:

FastAPI Depends
Database session
App instance import
services.py
Logic layer placeholder.

tests.py
Test file placeholder.

⚠️ Notes
This tool does not override the official fastapi CLI.
It is intentionally named start-fastapi to avoid conflicts.
Designed to work smoothly inside virtual environments.
🧠 Philosophy
This project follows a simple, explicit, and minimal approach.

You generate only what you need, and you stay in full control of your code.

📌 Roadmap (Optional)
[ ] Auto-register routers in main.py
[ ] Project-level scaffolding
[ ] Alembic integration
[ ] Typer-based FastAPI plugin
🤝 Contributing
Feel free to fork, improve, and submit pull requests.

Ideas and suggestions are always welcome.
