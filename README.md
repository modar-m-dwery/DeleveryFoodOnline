# Food Delivery App

This repository contains a food delivery app built using React Native for the frontend and Django with Django REST Framework for the backend.

## User Types

---

There are three different user types in this app: User, Restaurant, and Driver.

### User Account

- **Registration:** Users can register through the registration screen.
- **Features:**
  - Browse or search through restaurants and foods.
  - Create orders.
  - Follow order status.
  - Rate restaurants.
  - Add payment and address information.

### Restaurant Account

- **Registration:** Currently, restaurant accounts need to be created from the backend.
- **Features:**
  - Add new food items.
  - View orders.
  - Change order status.
  - Assign drivers to orders.

### Driver Account

- **Registration:** Currently, driver accounts need to be created from the backend.
- **Features:**
  - View assigned orders.
  - Send GPS location.
  - Complete orders.

## Screenshots

![Home Screen](images/home_screen.png)
![Restaurant List](images/restaurant_list.png)
![Order Tracking](images/order_tracking.png)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd yourrepository
   ```

3. **Backend Setup:**

   - Create a virtual environment and activate it:
     ```bash
     python -m venv env
     source env/bin/activate  # On Windows, use `env\Scripts\activate`
     ```
   - Install the required packages:
     ```bash
     pip install -r requirements.txt
     ```
   - Run migrations:
     ```bash
     python manage.py migrate
     ```
   - Create a superuser:
     ```bash
     python manage.py createsuperuser
     ```
   - Start the development server:
     ```bash
     python manage.py runserver
     ```

4. **Frontend Setup:**

   - Navigate to the React Native project directory:
     ```bash
     cd frontend
     ```
   - Install the required packages:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm start
    
