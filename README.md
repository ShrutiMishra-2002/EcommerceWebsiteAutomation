# EcommerceWebsiteAutomation

This project automates the testing of an e-commerce website using **Selenium WebDriver** with **Java**. The test cases cover essential functionalities such as login, applying filters, adding products to the cart, checkout, and logout.

## Features

- **Login Functionality**: Verifies that the login process works correctly.
- **Filter Functionality**: Applies filters to the product list and checks if products are displayed in ascending order of price.
- **Add to Cart Functionality**: Verifies the correct addition of products to the cart.
- **Checkout Functionality**: Validates the checkout process for accurate payment flow and order confirmation.
- **Logout Functionality**: Verifies that users can log out successfully.

## Test Cases

1. **Login Functionality**  
   Verifies the login functionality to ensure that users can authenticate successfully.

2. **Applying Filter Functionality**  
   Applies filters to the products and ensures that they are displayed in ascending order of price.

3. **Add to Cart Functionality**  
   Adds products to the cart and verifies that the products are correctly added and the cart updates accordingly.

4. **Checkout Functionality**  
   Simulates the checkout process and ensures that the payment flow works correctly and order confirmation is received.

5. **Logout Functionality**  
   Verifies that the logout functionality works, ensuring that users are logged out properly.

## Technologies Used

- **Selenium WebDriver**: For automating the browser interactions.
- **Java**: Programming language for implementing the test scripts.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ShrutiMishra-2002/EcommerceWebsiteAutomation.git

2. Navigate to the project directory:
   ```bash
   cd EcommerceWebsiteAutomation
3.Run the test cases using a test runner like JUnit or TestNG:
   ```bash
   mvn test

