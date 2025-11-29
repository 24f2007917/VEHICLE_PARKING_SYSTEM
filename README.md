
# 🚗 Parkkro – Modern Parking System

A smart, eco-friendly, and user-centric Flask-based vehicle parking management system. Features real-time availability, admin/user roles, a Green Card reward system, and more.

---

## 📌 Key Features

### 👨‍💼 Admin Panel

* Manage users, parking lots, and reservations
* Real-time parking stats
* Add/Edit/Delete parking spots

### 🙋‍♂️ User Dashboard

* Book and release parking spots
* View booking history
* Auto billing based on usage
* Green Card reward system


## 🛠️ Tech Stack

| Layer        | Tech Used                  |
| ------------ | -------------------------- |
| **Backend**  | Python (Flask), SQLAlchemy |
| **Frontend** | HTML5, CSS3                |
| **Database** | SQLite                     |

---

## 🧱 Folder Structure

```
VEHICLE_PARKING_SYSTEM/
│
├── app.py                 # Main Flask app entry
├── setup_db.py            # DB setup script
├── requirements.txt       # Dependencies
├── README.md              # Documentation
├── instance/              # Database location
│
├── models/                # SQLAlchemy models
│
├── static/
│   └── css/
│       └── styles.css     # Styling
│
├── templates/
│   ├── all Html             # Admin + user HTML templates
│             
│
└── venv/                  # Virtual environment
```

---

## 🔐 Default Credentials

| Role  | Username                 | Password   |
| ----- | ------------------------ | ---------- |
| Admin | `admin`                  | `admin123` |
| User  | Register via `/register` |            |

---


## 🧾 Database Models

* `users` – Stores user credentials and Green Card status
* `parking_lots` – Lot info, capacity, etc.
* `parking_spots` – Individual spot details
* `reservations` – Booking records
* `green_cards` – Green membership and points
* `discount_coupons` – Redeemable rewards

---

## 🧪 Local Development Setup

```bash
# Clone the repository (if applicable)
git clone <repo-url>
cd VEHICLE_PARKING_SYSTEM/

# Create virtual environment
python -m venv venv
# Activate (Windows)
venv\Scripts\activate
# or (Linux/Mac)
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Initialize the database (if setup_db.py exists)
python setup_db.py

# Run the server
python app.py
```

> Access the app at: [http://localhost:5000](http://localhost:5000)

---

## 🧑‍💻 Maintainer

**Name:** Ujjwal Singh
**Email:** [24f2007917@ds.study.iitm.ac.in](mailto:24f2007917@ds.study.iitm.ac.in)
**Project Name:** `Parkro – Modern Parking System`

---