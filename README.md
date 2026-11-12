# Full-Stack E-Commerce Web Application

A web-based e-commerce application developed using **Python and Django**, providing essential online shopping functionality, including user authentication, product browsing, shopping cart management, checkout and order processing.

## Overview

The project demonstrates the development of a full-stack web application using Django for server-side functionality and database management, alongside HTML, CSS, JavaScript and Bootstrap for the frontend.

It provides an integrated shopping experience in which users can browse products, search and filter listings, manage their shopping carts and place orders.

## Features

- **User Authentication:** User registration, login and account management.
- **Customer Management:** Customer profiles and address management.
- **Product Catalogue:** Browse available products and view product information.
- **Product Search:** Search for products by title.
- **Product Filtering:** Filter products using available brand and price criteria.
- **Shopping Cart:** Add products, update quantities and manage cart items.
- **AJAX Cart Operations:** Perform dynamic cart updates using asynchronous requests and JSON responses.
- **Checkout:** Process shopping cart items and place orders.
- **Order Management:** View order history and order information.
- **Admin Management:** Manage application data through Django's administration interface.

## Technology Stack

| Component | Technology |
|---|---|
| Programming Language | Python |
| Backend Framework | Django |
| Database | SQLite |
| Frontend | HTML, CSS, JavaScript |
| UI Framework | Bootstrap |
| Database Interaction | Django ORM |
| Asynchronous Operations | AJAX, JSON |

## Application Architecture

The application follows Django's **Model-View-Template (MVT)** architecture.

- **Models:** Define and manage application data, including customers, products, shopping carts and orders.
- **Views:** Handle application logic, user requests, product operations and order processing.
- **Templates:** Render the user interface using Django templates, HTML, CSS, JavaScript and Bootstrap.
- **Database:** SQLite stores application data, accessed through Django's Object-Relational Mapping (ORM).

AJAX requests and JSON responses support dynamic shopping cart interactions without requiring a complete page reload for each operation.

## Installation and Setup

### Prerequisites

- Python
- pip
- Git

### 1. Clone the repository

```bash
git clone https://github.com/404ErrorBrainNotFound/Full-Stack-main.git
```

### 2. Navigate to the project directory

```bash
cd Full-Stack-main/shopping
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**
```bash
venv\Scripts\activate
```

**Linux / macOS**
```bash
source venv/bin/activate
```

### 4. Install dependencies

Install the required packages used by the project. If a `requirements.txt` file is available:

```bash
pip install -r requirements.txt
```

### 5. Apply database migrations

```bash
python manage.py migrate
```

### 6. Start the development server

```bash
python manage.py runserver
```

Open the application at:

`http://127.0.0.1:8000/`

*Note: The installation steps assume the Django project configuration and dependencies are available in the repository. Additional configuration may be required depending on the local environment.*

## Learning Outcomes

The project provided practical experience with:

- Developing a full-stack web application using Django.
- Working with Django's MVT architecture and ORM.
- Designing and managing relational application data.
- Implementing user authentication and customer management.
- Integrating frontend components with backend functionality.
- Handling asynchronous requests and JSON responses.
- Implementing product browsing, cart operations and order workflows.
- Debugging and integrating different application components.

## Project Information

**Project Type:** Individual Final-Year Project  
**Domain:** Full-Stack Web Development  
**Primary Language:** Python  
**Framework:** Django
