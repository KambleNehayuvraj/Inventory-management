📦 Inventory Management Application

A full-stack Inventory Management System built using Django REST Framework (Backend) and Next.js (Frontend).
The application supports complete CRUD operations, analytics dashboard, and third-party API integration.

🚀 Live Deployment Links

Frontend (Live UI):
👉 https://REPLACE_WITH_FRONTEND_URL

Backend API:
👉 https://REPLACE_WITH_BACKEND_URL

🛠️ Tech Stack

Frontend

Next.js 16

TypeScript

Tailwind CSS

Axios

Backend

Django 6

Django REST Framework

PostgreSQL (Supabase)

Third-Party API

Currency Exchange API

✨ Features

Create, Read, Update, Delete products (CRUD)

Inventory dashboard with analytics

Low stock monitoring

Category-wise product count

Third-party currency API integration

REST API architecture

Responsive UI

📂 Project Structure

inventory-management-app
├── backend
│ ├── core
│ ├── inventory
│ ├── manage.py
│ └── requirements.txt
│
├── frontend
│ ├── app
│ ├── components
│ ├── services
│ └── package.json

⚙️ Backend Setup (Local)

Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

cd inventory-management-app/backend

Create virtual environment
python -m venv venv

Activate virtual environment
Windows: venv\Scripts\activate
Mac/Linux: source venv/bin/activate

Install dependencies
pip install -r requirements.txt

Create .env file inside backend folder

DEBUG=True
SECRET_KEY=your_secret_key

DB_NAME=your_db_name
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_HOST=your_db_host
DB_PORT=5432

Run migrations
python manage.py migrate

Start backend server
python manage.py runserver

Backend runs on:
http://127.0.0.1:8000

🎨 Frontend Setup (Local)

Navigate to frontend folder
cd ../frontend

Install dependencies
npm install

Create .env.local

NEXT_PUBLIC_API_URL=http://127.0.0.1:8000/api/

Start frontend
npm run dev

Frontend runs on:
http://localhost:3000

📊 Dashboard & Reports

Dashboard displays:

Total products

Low stock products

Category-wise product count

Dashboard URL:
/dashboard

🔄 How to Test CRUD Operations

Create Product

Open frontend

Click “Add Product”

Fill product details

Submit form

View Products

Product list appears on home page

Update Product

Click Edit

Modify product

Save changes

Delete Product

Click Delete

Confirm deletion

🌍 Third-Party API Feature

Currency exchange API integration.

Endpoint:
/api/currency/

Displays live currency data.

🗄️ Database

PostgreSQL hosted on Supabase

Django ORM used for database operations

🚀 Deployment Notes

Backend

Deployed on Render

Connected to Supabase PostgreSQL

Frontend

Deployed on Vercel / Render Static

🧪 Testing Guide (Submission Requirement)

Open live frontend link

Perform Create → View → Update → Delete operations

Open dashboard and verify analytics update

Test third-party currency API

📌 API Endpoints

Products
GET /api/products/
POST /api/products/
PUT /api/products/{id}/
DELETE /api/products/{id}/

Dashboard
GET /api/dashboard/

Currency
GET /api/currency/

📹 Screen Recording

A 3–5 minute screen recording demonstrates:

Live application access

Full CRUD functionality

Dashboard & reports

Third-party API working

👩‍💻 Author

Neha Kamble

⭐ Notes

Clean and scalable full-stack architecture

REST-based backend

Production-ready UI
