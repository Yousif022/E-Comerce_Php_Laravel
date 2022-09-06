<p align="left"><img src="https://user-images.githubusercontent.com/91213036/188661557-3aa012a7-517e-4f24-b440-edc8f1022637.png" alt="Laravel Ecommerce Project " width="500"></p>

 


## Features
- User Dashboard
- Admin Dashboard
- Mobile-Friendly Website
- 3 Step Booking Process
- Order Tracking
- Email Notifications
- Subscriber Form
- A product search form
- Payment Gateway(PayU) Integrated
- Shopping Cart in a Responsive Layout
- Pre-Defined Content with High-Resolution Photos
- Search engine optimization (SEO) for Products
- Recommendations and related products in our categories

## Requirements 
-   Laravel <=5.8
-   PHP <= 7.1.3
-   Composer Version 2 
## Installation Steps 

1.  <code> composer create-project rahulvijayam/ecommerce </code>
2. Create database for  your project with the name as <code>gainaloe</code>
3. Now Run <code>php artisan migrate</code> command for creating all the tables 
4. Add your email credentials in <code>.env</code> file
5. Add PayuMoney <code>merchant key and salt</code> on <code> config/indipay.php</code> file at line number 30 and 31
6. Start yor project using <code>php artisan serve</code>

## Generate Sample Data ( Optional)
1. Remove tables(products, users) from the  database.
2. Run two files present in this link https://github.com/RahulVijayam/ecommerce/tree/master/public/sql on your database
3. Finished, Now Check it in your browser using http://127.0.0.1:8000

