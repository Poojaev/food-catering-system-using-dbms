# Online Food Catering System using DBMS

## Introduction
The **Online Food Catering System** is a database-driven web application that allows users to order food online, manage catering services, and handle transactions efficiently. The system provides an intuitive interface for customers, administrators, and catering staff, ensuring a seamless experience.

## Features
- **User Management**: Customers can register, log in, and manage their profiles.
- **Menu Management**: Admins can add, update, and remove food items from the menu.
- **Order Processing**: Users can place, modify, and cancel orders.
- **Payment Integration**: Secure payment gateway for online transactions.
- **Admin Dashboard**: View sales reports, manage orders, and handle user queries.
- **Database Management**: Ensures data consistency and integrity.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: PHP/Python (Flask or Django)
- **Database**: MySQL / Oracle / PostgreSQL
- **Version Control**: Git & GitHub

## Database Structure
The system follows a relational database model with tables such as:
- **Users** (User_ID, Name, Email, Password, Role)
- **Menu** (Item_ID, Name, Description, Price, Category)
- **Orders** (Order_ID, User_ID, Total_Amount, Status, Order_Date)
- **Order_Items** (Order_Item_ID, Order_ID, Item_ID, Quantity)
- **Payments** (Payment_ID, Order_ID, Amount, Payment_Method, Payment_Status)

## Installation & Setup
### Prerequisites:
- Install **XAMPP/WAMP** (for MySQL & PHP)
- Install **Python & Flask/Django** (if using Python backend)
- Install **Git** (for version control)

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/food-catering-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd food-catering-system
   ```
3. Set up the database:
   - Import `database.sql` into MySQL or configure your preferred DBMS.
   - Update `config.php` or `.env` file with database credentials.
4. Start the server:
   ```bash
   php -S localhost:8000  # For PHP backend
   ```
   OR
   ```bash
   python app.py  # For Flask backend
   ```
5. Open the browser and visit `http://localhost:8000`

## Usage
- **Customer**: Sign up, browse menu, place orders, and make payments.
- **Admin**: Manage menu, process orders, and track payments.
- **Catering Staff**: View and prepare orders.

## Future Enhancements
- Implement AI-based recommendation system for users.
- Add multi-language support.
- Integrate SMS/email notifications for order status updates.

## Contributors
- [Your Name]
- [Other Team Members]

## License
This project is licensed under the MIT License.

## Contact
For any issues or inquiries, reach out to **your-email@example.com**.

