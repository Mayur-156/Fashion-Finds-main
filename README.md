# 👗 Fashion Finds – E-Commerce Web App

**Fashion Finds** is a complete fashion e-commerce website built using **Flask** (Python web framework) as part of an internship project at **Infosys**. This project simulates a functional online fashion store with key features like user authentication, product browsing, cart and wishlist management, and admin controls.

---

## 🚀 Project Objective

To design and implement a scalable, secure, and user-friendly e-commerce platform for fashion products using **Python Flask**, HTML/CSS, and a relational database. The platform supports user login, product listing, shopping cart, and wishlist features.

---

## 🧩 Features

### 👥 User Module
- User Signup/Login/Logout
- Role-based access control (User / Admin / Delivery Agent)
- Profile management
- Wishlist functionality
- Shopping cart functionality
- Order placement

### 🛒 Product Module
- View products by brand (e.g., Puma, Adidas, H&M)
- View product details (image, price, description, category)
- Filter products by category: Men, Women, Kids, Accessories, Shoes
- Add/remove items to/from cart and wishlist

### 🧑‍💼 Admin Module
- Admin dashboard with inventory management
- Add/Edit/Delete products, brands, categories
- View user data, orders, and system logs

### 🚚 Delivery Agent Module
- View assigned orders
- Update delivery status
- Access to delivery dashboard

### 📦 Cart & Wishlist System
- Add/remove items from Cart or Wishlist
- View Cart and Wishlist pages
- Checkout system (front-end mockup)

### 📊 Dashboard Analytics (Planned/Future Scope)
- Visualized order stats
- Product trend insights (dummy or future implementation)

---

## 📂 Project Structure
Fashion-Finds-main/
│
├── app/
│ ├── init.py # Flask app setup
│ ├── models.py # SQLAlchemy models (User, Product, Cart, etc.)
│ ├── views.py # Main application routes
│ ├── forms.py # Flask-WTF forms
│ ├── admin.py # Admin routes
│ ├── auth.py # Authentication logic
│
├── media/ # Product images, user uploads
├── static/ # CSS, JavaScript, image assets
├── templates/ # Jinja2 HTML templates
│
├── tests/ # Unit testing files
├── main.py # Application entry point
├── requirements.txt # Python dependencies
├── README.md # Project documentation

🛠️ Technologies Used

- Backend: Python, Flask, SQLAlchemy
- Frontend: HTML5, CSS3, Bootstrap, JavaScript
- Database: SQLite (development) or MySQL (optional)
- Authentication: Flask-Login, role-based access
- Forms: Flask-WTF
- Hosting: Local Flask development server (can be deployed to Heroku/Render)


  ⚙️ Installation & Setup

1. Clone the repo:
   bash
   git clone https://github.com/Mayur-156/Fashion-Finds-main.git
   cd Fashion-Finds-main
   
3. Create and activate a virtual environment:
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   
4. Install the required packages:
   pip install -r requirements.txt
   
5. Run the application:
   python main.py
   
6. Open in browser:
   http://localhost:5000/

✅ Accomplishments
Developed as part of Infosys Internship Capstone Project.

Implemented full-stack features using Flask MVC architecture.

Ensured clean code structure, modularity, and reusability.

📌 Future Enhancements
Payment gateway integration (e.g. Stripe/Razorpay)

Email notifications and OTP login

Rating & review system

Advanced analytics dashboard for admin

Progressive Web App (PWA) version

👤 Author
Mayur Kadam
Intern @ Infosys
GitHub Profile



---

