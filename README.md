# E-commerce Website
Fully functional E-commerce website with Stripe Online Payments, Admin Analytics Dashboard, Reporting and more, built with Laravel, Vue.js, TailwindCSS and Aplpine <br>

## Tech Stack
-   Laravel
-   Vue.js
-   Alpine.js
-   TailwindCSS

## Features
### Landing Page
-   Output all database products with pagination
-   Add to Cart functionality
-   Responsive Design with Tailwind.css

### Cart Page
-   Change quantity of the items
-   Remove items from cart
-   Proceed to checkout page
-   Send email to admin users on new orders

### My Orders Page
-   Output customer orders with pagination
-   Pay unpaid orders
-   Click to view order details

### Analytics Dashboard
-   Overall information about active customers, paid orders, total income
-   Order distribution by countries
-   Information about latest orders and customers
-   Change date range period to update data

### All Orders in Admin Panel
-   View all orders with pagination, sorting and filtering
-   Click each order to view all details of the order
-   Update order status into shipping or completed
-   Send email to customer when order status is updated

### Dedicated page for reports
-   Number of new orders by day
-   Number of new customers by day
-   Update date range period



## Demo
-   Admin Panel: https://admin.lcommerce.net
    ```
    Email: admin@example.com
    Password: admin123
    ```

-   Website: https://lcommerce.net

    ```
    Email: user1@example.com
    Password: useruser1


    Email: user2@example.com
    Password: useruser2
    ```


## How to Run
### Requirements
Make sure you have environment setup properly. 
-   MySQL
-   PHP8.1
-   Node.js
-   composer

### Install Laravel Website + API
1. Download the project (or clone using GIT)
2. Copy `.env.example` into `.env` and configure database credentials
3. Navigate to the project's root directory using terminal
4. Run `composer install`
5. Set the encryption key by executing `php artisan key:generate --ansi`
6. Run migrations `php artisan migrate --seed`
7. Start local server by executing `php artisan serve`
8. Open new terminal and navigate to the project root directory
9. Run `npm install`
10. Run `npm run dev` to start vite server for Laravel frontend

### Install Vue.js Admin Panel
1. Navigate to `backend` folder
2. Run `npm install`
3. Copy `backend/.env.example` into `backend/.env`
4. Make sure `VITE_API_BASE_URL` key in `backend/.env` is set to your Laravel API host (Default: http://localhost:8000)
5. Run `npm run dev`
6. Open Vue.js Admin Panel in browser and login with
    ```
    admin@example.com
    admin123
    ```
