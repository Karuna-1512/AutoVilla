
# AutoVilla 🚗🏍️

AutoVilla is a Django-based web application designed as a vehicle marketplace. It allows users to explore, search, and filter available cars and bikes for sale or rent.

## 🔧 Tech Stack

- **Backend:** Django, Python
- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Database:** SQLite (can be switched to PostgreSQL/MySQL)
- **Other Tools:** Git, GitHub

## 📦 Features

- Dynamic vehicle listings
- Categories: Cars & Bikes
- Featured vehicle cards
- Responsive design
- Image galleries
- User authentication (coming soon)
- Wishlist or booking system (planned)

## 🛠️ Setup Instructions

```bash
git clone https://github.com/Karuna-1512/autovilla.git
cd autovilla
python -m venv venv
venv\Scripts\activate  # For Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
