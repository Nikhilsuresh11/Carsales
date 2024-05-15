---

# Used Cars Price Prediction

## Overview

This project is a comprehensive car sales website built using Django, a high-level Python web framework. The website facilitates buying and selling of used cars, along with a unique feature of predicting car prices using linear regression based on their details. The user interface is designed with HTML and CSS to provide a seamless and visually appealing experience.

![Car Sales Website Demo](demo.gif)

## Features

- **Car Listing:** Browse through a wide range of used cars available for sale.
- **Price Prediction:** Predict the price of a car based on its details using linear regression.
- **Car Details Upload:** Allow users to upload their car details for selling purposes.
- **User Authentication:** Secure user authentication system for account creation and login.
- **Sleek UI:** Modern and intuitive user interface design using HTML and CSS.

## Installation

To run this car sales website locally, follow these steps:

1. Clone this repository to your local machine:

    ```
    git clone https://github.com/Nikhilsuresh11/Carsales.git
    ```

2. Navigate to the project directory:

    ```
    cd Carsales
    ```

3. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

4. Apply migrations to set up the database:

    ```
    python manage.py migrate
    ```

5. Create a superuser account for accessing the Django admin panel:

    ```
    python manage.py createsuperuser
    ```

6. Start the Django development server:

    ```
    python manage.py runserver
    ```

Once the server runs, open your web browser and navigate to `http://localhost:8000` to access the car sales website.

## Usage

- **Buying Cars:** Browse the available car listings, view details, and contact sellers.
- **Price Prediction:** Use the price prediction feature to estimate the price of a car based on its specifications.
- **Selling Cars:** Upload your car details along with images for listing it for sale.

