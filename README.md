# Week 2: Core Backend Concepts (DRF Django)

This repository serves as a daily technical log and knowledge base of the core backend concepts learned and implemented while building the **Task Manager** backend. 

Instead of just writing code, each day focuses on breaking down the underlying architectural patterns, database optimizations, and security mechanics provided by Django REST Framework (DRF).

## 📌 Project Context
All concepts documented here were explored and tested through the lens of a **Task Management System** API—covering everything from user task assignments and status updates to complex filtering, performance tuning, and endpoint protection.

---

## 📅 Day-by-Day Learning Log

* 📂 **[Day 1](./day1.md)** — Core HTTP Protocols, the Request/Response lifecycle, and mapping them to DRF's `APIView` workflow.
* 📂 **[Day 2](./day2.md)** — RESTful API Design: Structuring Task and User resources using DRF Serializers, ModelSerializers, ViewSets, and Routers.
* 📂 **[Day 3](./day3.md)** — Relational Data & Database Optimization: Handling Task-User relationships in the Django ORM, writing efficient queries (`select_related` and `prefetch_related`), and pagination.
* 📂 **[Day 4](./day4.md)** — API Security & Authentication: Protecting task endpoints using JWT (`django-rest-framework-simplejwt`) and implementing custom object-level permissions (e.g., ensuring users can only view/edit their own tasks).
* 📂 **[Day 5](./day5.md)** — Middleware & Error Handling: Crafting custom DRF exception handlers to return consistent, structured error responses for bad task operations.
* 📂 **[Day 6](./day6.md)** — Asynchronous Operations & Signals: Offloading heavy operations (like sending email notifications for overdue tasks) out of the main request-response cycle using Django Signals and background tasks.

---

## 🛠️ Tech Stack Covered
* **Framework:** Django REST Framework (DRF)
* **Language:** Python 3.11+
* **Authentication:** JWT (`django-rest-framework-simplejwt`)
* **Database:** SQLite / PostgreSQL

---

## ⚙️ Local Development Setup

To look through the implementations or run the backend locally:

```bash
# Clone the repository
git clone [https://github.com/imad-ship-it/week2-backend-concepts.git](https://github.com/imad-ship-it/week2-backend-concepts.git)
cd week2-backend-concepts

# Set up and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install required dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the development server
python manage.py runserver
