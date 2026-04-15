AgroMarket – Agricultural E-Commerce Platform

Overview

AgroMarket is a cloud-based e-commerce platform that enables users to buy and sell agricultural products online. It is built using the Django web framework and deployed on AWS cloud services to ensure scalability, reliability, and performance.

 Features:

User authentication and secure login system
Browse and purchase agricultural products
Order management and tracking
Admin dashboard for managing:
Products (CRUD)
Customers
Orders
Feedback
 Cloud-based image storage using AWS S3
 Email notifications using AWS SNS
 Automatic invoice generation using AWS Lambda
 Export order data to CSV using custom PyPI library
 Tech Stack

Frontend & Backend

Python (Django)

Database

PostgreSQL (AWS RDS)

Cloud Services (AWS)

Elastic Beanstalk – Deployment
S3 – Image storage
RDS – Database
SNS – Email notifications
API Gateway – API management
Lambda – Serverless functions

Other Tools

GitHub Actions (CI/CD)
Custom PyPI Package: export-orders-lib
Installation (Local Setup)
Clone the repository:
git clone https://github.com/your-username/agromarket.git
cd agromarket
Create virtual environment:
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate
Install dependencies:
pip install -r requirements.txt
Run migrations:
python manage.py migrate
Start server:
python manage.py runserver
Live Demo

 http://agromarket.us-east-1.elasticbeanstalk.com

 Project Structure
agromarket/
│── app/
│── static/
│── media/
│── templates/
│── manage.py
│── requirements.txt
Key Functional Modules
User Module
Register/Login
Browse products
Place orders
View order history
Admin Module
Manage products, customers, and orders
View feedback
Export order data (CSV)
Custom Library
export-orders-lib
Used to export order data into CSV format
Improves reporting and data management

PyPI Link: https://pypi.org/project/export-orders-lib/

CI/CD Pipeline
Automated using GitHub Actions
On every push:
Build runs automatically
Application deploys to AWS Elastic Beanstalk         ___        ______     ____ _                 _  ___  
        / \ \      / / ___|   / ___| | ___  _   _  __| |/ _ \ 
       / _ \ \ /\ / /\___ \  | |   | |/ _ \| | | |/ _` | (_) |
      / ___ \ V  V /  ___) | | |___| | (_) | |_| | (_| |\__, |
     /_/   \_\_/\_/  |____/   \____|_|\___/ \__,_|\__,_|  /_/ 
 ----------------------------------------------------------------- 


Hi there! Welcome to AWS Cloud9!

To get started, create some files, play with the terminal,
or visit https://docs.aws.amazon.com/console/cloud9/ for our documentation.

Happy coding!
