# 🎬 Netflix Clone - Full Stack Project (Django + PostgreSQL)

A fully functional Netflix-inspired web app built using **Django (Python)** for the backend and **HTML, CSS, JavaScript** for the frontend.  
This project includes movie browsing by genre, search, a “My List” feature, user login, and dynamic content — all backed by a **PostgreSQL** database.

---

## 🔥 Features

- 🎥 Netflix-style UI with TailwindCSS
- 🔍 Search movies by title
- 🏷️ Filter by genre
- ✅ Add movies to personal "My List"
- 🔐 User login/logout system
- 🎬 Dynamic featured movie section
- 🛠️ Admin panel to upload and manage movies
- 💾 PostgreSQL for data persistence

---

## 🛠️ Tech Stack

| Layer        | Technology                  |
|--------------|------------------------------|
| 💻 Frontend   | HTML, TailwindCSS, JavaScript |
| ⚙️ Backend    | Django (Python)              |
| 🗃️ Database   | PostgreSQL                   |

---

## 📸 Screenshots

> _Add screenshots or a demo GIF here to visually show your project_

---

## 🚀 Getting Started (Run Locally)

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/netflix-clone-django.git
cd netflix-clone-django 
```
### 2. Create and Activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
### 4. Setup PostgreSQL
- Create a database named netflix_clone
- In settings.py, update:
```bash
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'netflix_clone',
        'USER': 'your_db_user',
        'PASSWORD': 'your_db_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
```
### 5. Run Migrations & Create Superuser

```bash
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
```
### 6. Start the Server

```bash
python manage.py runserver
```
---
## 👨‍💻 Admin Access
Login to Django Admin:
- Visit: http://127.0.0.1:8000/admin/
- Use the superuser credentials you created
You can:
- Add movies
- Assign genres
- Upload posters and cover images
---
## 📂 Project Structure
```bash
netflix-clone/
├── templates/
│   ├── index.html
│   ├── login.html
│   └── movie_detail.html
├── static/
│   ├── css/
│   └── js/
├── movies/
│   ├── models.py
│   ├── views.py
│   └── urls.py
└── manage.py
```
---
## 💡 Future Improvements
- ⏯️ Add real video streaming (MP4 / HLS)
- 🧠 AI movie recommendation system
- 📝 Reviews & Ratings system
- 📧 Email-based user registration & verification
---
## 🙋‍♂️ Author
Praveen Kumar Gone
🧑‍💻 Aspiring Python Backend Developer
📧[praveenkumargone229@gmail.com]
🌐[www.linkedin.com/in/gonepraveen]

## License
This project is for educational and personal portfolio use only.
Netflix™ is a registered trademark of Netflix Inc.
```bash

---

✅ Just copy and paste this into a file named `README.md` in your project root.

Let me know if you want:
- Demo image embed help  
- Requirements.txt auto generator  
- GitHub Pages deployment

I'm here to finish this perfectly for your hiring ❤️
```
---


