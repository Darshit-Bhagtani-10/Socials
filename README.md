# 📱 Socials - Influencer & Sponsor Collaboration Platform

![License](https://img.shields.io/badge/license-MIT-green)
![Django](https://img.shields.io/badge/Django-4.x-blue)
![Python](https://img.shields.io/badge/Python-3.10+-blue)

> A full-featured web application connecting influencers and sponsors through personalized content collaboration, campaign management, and performance tracking.

---

## 🖼️ Project Preview

![Dashboard](screenshots/dashboard.png)
![Influencer Profile](screenshots/profile.png)
![Sponsor View](screenshots/sponsor-view.png)

---

## 🚀 Features

### 🔐 Authentication & Profiles

* Custom login/signup flows
* Email verification
* Editable influencer and sponsor profiles

### 🧑‍💼 Sponsor Panel

* Create and manage ad campaigns
* Filter influencers by content niche
* Save & track sponsored posts

### 📱 Influencer Panel

* Upload content posts (Reels, Shorts, Videos, etc.)
* Track engagement and sponsorship offers
* Receive campaign notifications

### 💬 Notifications & Transactions

* Real-time updates on new collaborations
* Transparent transaction history

---

## 🛠️ Tech Stack

| Category       | Tools Used                 |
| -------------- | -------------------------- |
| Backend        | Django, SQLite             |
| Frontend       | HTML5, CSS3, Bootstrap     |
| Authentication | Django Auth, Custom Views  |
| Deployment     | Heroku-ready with Procfile |

---

## ⚙️ Getting Started

### Prerequisites

* Python 3.10+
* pip

### Installation

```bash
# Clone the repository
$ git clone https://github.com/yourusername/Socials.git
$ cd Socials-main

# Install dependencies
$ pip install -r requirements.txt

# Run migrations
$ python manage.py migrate

# Start the development server
$ python manage.py runserver
```

---

## 🧪 Sample Credentials (For Demo)

| Role       | Username | Password     |
| ---------- | -------- | ------------ |
| Sponsor    | sponsor1 | sponsor\@123 |
| Influencer | inflncr1 | inflncr\@123 |

---

## 📂 Project Structure

```
Socials-main/
├── app/                  # Core Django app (models, views, templates)
├── company/              # Sponsor-side logic and templates
├── templates/            # UI templates
├── static/               # CSS, JS, images
├── manage.py             # Django entry point
├── requirements.txt      # Dependencies
└── Procfile              # Heroku deployment
```

---
