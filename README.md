
# Restaurant Table Booking Python Web App
[![JavaScript](https://img.shields.io/badge/javascript-%2320232a.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Python](https://img.shields.io/badge/python-%2320232a.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![HTML](https://img.shields.io/badge/html-%2320232a.svg?style=for-the-badge&logo=html5&logoColor=%23E34F26)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/css-%2320232a.svg?style=for-the-badge&logo=css3&logoColor=%231572B6)](https://developer.mozilla.org/en-US/docs/Web/CSS)


## Description
This Python web application allows customers to book tables at a restaurant online. It provides a user-friendly interface for customers to view available tables, select a desired time slot, and make a reservation. The app also includes an admin dashboard for restaurant staff to manage table availability and view customer bookings.

## Features
- Table Availability: Customers can view the available tables and their availability status.
- Table Booking: Customers can select a date and time slot, and make a reservation for a specific table.
- Admin Dashboard: Restaurant staff can manage table availability, view and manage customer bookings.
- Email Notifications: Automated email notifications sent to customers upon successful booking.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/IPH-Technologies-Pvt-Ltd/Restaurant-Website-Django.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Restaurant-Website-Django
   ```

3. Create and activate a virtual environment (optional, but recommended):
   ```bash
   python3 -m venv env
   source env/bin/activate
   ```

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Configure the database:
   - Create a PostgreSQL database and update the database configuration in `config.py`.

6. Run database make migrations:
   ```bash
   python manage.py makemigrations
   ```

7. Run database migrations:
   ```bash
   python manage.py migrate
   ```

8. Start the development server:
   ```bash
   python manage.py runserver
   ```

9. Open the web app in your browser:
   ```
   http://localhost:8000/
   ```

## Usage
- Upon accessing the web app, customers can create an account or log in if they already have one.
- Customers can view the available tables, select a date and time slot, and make a reservation.
- Restaurant staff can access the admin dashboard to manage table availability and view customer bookings.

## Technologies Used
- Python
- Django
- HTML
- CSS
- JavaScript
- SQLite3

## Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please submit an issue or open a pull request.

## Video


https://github.com/IPH-Technologies-Pvt-Ltd/Restaurant-Website-Django/assets/130441026/366752de-7c7f-4902-a703-0f94faf5e538


## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any questions or inquiries, please contact [hr@iphtechnologies.com](mailto:hr@iphtechnologies.com)
