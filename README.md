# 🛒 NexMart - Curated Home & Living Marketplace

NexMart is a modern, multi-vendor e-commerce platform dedicated to connecting independent artisans with customers who appreciate unique, handcrafted home and living products. Built with a robust Django backend and a dynamic React frontend, NexMart offers a seamless shopping experience.

## ✨ Features

-   **Curated Marketplace**: A selection of high-quality, artisanal products.
-   **Multi-Vendor Support**: Independent vendors can register, manage their shops, and sell products.
-   **User Accounts**: Secure user registration, login, and profile management.
-   **Product Discovery**: Advanced search, filtering, and categorization.
-   **Shopping Cart**: Easy-to-use cart and checkout process.
-   **Responsive Design**: A beautiful, mobile-friendly interface.

## 🛠️ Tech Stack

### Backend
-   **Framework**: Django & Django REST Framework
-   **Database**: PostgreSQL / SQLite (for development)
-   **Authentication**: JWT (JSON Web Tokens)
-   **Admin**: Jazzmin for a polished admin interface

### Frontend
-   **Framework**: React (Vite)
-   **Styling**: Tailwind CSS
-   **State Management**: React Context API
-   **Routing**: React Router

## 📂 Project Structure

```
nexmart/
├── backend/                # Django Backend
│   ├── apps/               # Django Apps (products, vendors, users, etc.)
│   ├── core/               # Project Configuration (settings, urls, etc.)
│   └── manage.py           # Django management script
├── frontend/               # React Frontend
│   ├── src/                # Source code
│   │   ├── components/     # Reusable components
│   │   ├── pages/          # Page components
│   │   └── services/       # API services
│   └── package.json        # Frontend dependencies
└── README.md               # Project Documentation
```

## 🚀 Getting Started

### Prerequisites
-   Python 3.8+
-   Node.js 16+
-   npm or yarn

### Backend Setup

1.  Navigate to the backend directory:
    ```bash
    cd backend
    ```

2.  Create and activate a virtual environment:
    ```bash
    python -m venv venv
    # Windows
    venv\Scripts\activate
    # macOS/Linux
    source venv/bin/activate
    ```

3.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4.  Apply database migrations:
    ```bash
    python manage.py migrate
    ```

5.  Run the development server:
    ```bash
    python manage.py runserver
    ```

### Frontend Setup

1.  Navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2.  Install dependencies:
    ```bash
    npm install
    ```

3.  Start the development server:
    ```bash
    npm run dev
    ```

## 📝 Configuration

Environment variables can be configured in the backend `.env` file and frontend `.env` file (if applicable). Refer to the example configuration files for details.

---

© 2025 NexMart. All rights reserved.

## Recent Updates
- Improved mobile responsiveness
- Optimized API response times

<!-- Added documentation for deployment and local setup -->
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
