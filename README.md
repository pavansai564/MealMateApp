MealMate – Online Food Ordering System

MealMate is a full-stack food ordering web application that allows users to browse restaurants, explore menus, add food items to cart, and complete payments using Razorpay.
The platform also includes an Admin Dashboard to manage restaurants and menus.

🚀 Features
👤 User Features

User Registration & Login

Browse available restaurants

View restaurant menus with images and prices

Add food items to cart

View cart and total bill

Secure checkout using Razorpay Payment Gateway

🛠️ Admin Features

Admin login

Add new restaurants

View all restaurants

Update or delete restaurants

Manage restaurant menus

🧰 Tech Stack

Backend: Django (Python)

Frontend: HTML, CSS, Bootstrap

Database: SQLite (can be upgraded to MySQL/PostgreSQL)

Payments: Razorpay

Authentication: Django Authentication System

📸 Project Screenshots
1️⃣ Welcome Page
<img width="2153" height="1339" alt="Screenshot 2026-01-04 182216" src="https://github.com/user-attachments/assets/60487c4f-923f-4f6b-a6e9-77b9ceeba558" />
This is the landing page of MealMate where users can either Sign Up or Sign In.
2️⃣ User Dashboard (Restaurant Listing)
<img width="2139" height="1325" alt="Screenshot 2026-01-04 182320" src="https://github.com/user-attachments/assets/60b64016-4f1f-43ec-83d2-2e0714593bdd" />
After login, users can view all available restaurants with:
Restaurant image
Cuisine type
Rating
Option to view menu
3️⃣ Restaurant Menu Page
<img width="2115" height="1329" alt="Screenshot 2026-01-04 182354" src="https://github.com/user-attachments/assets/74f30b7b-82cb-4c24-9a9a-c4bcc1cbca07" />
Displays the selected restaurant’s menu with:
Food images
Description
Price
Veg / Non-Veg indicator
Add to Cart option
4️⃣ Cart Page
<img width="2123" height="1335" alt="Screenshot 2026-01-04 182510" src="https://github.com/user-attachments/assets/e82df829-1da9-422c-82e9-de831520effc" />
Shows all selected food items with:
Item details
Individual prices
Total cart value
5️⃣ Checkout Page
<img width="2143" height="1293" alt="Screenshot 2026-01-04 182530" src="https://github.com/user-attachments/assets/e921b036-8f08-42c4-9c21-ad3478522bec" />
Displays order summary before payment and allows users to proceed with Razorpay.
6️⃣ Admin Dashboard
<img width="2154" height="1348" alt="Screenshot 2026-01-04 182559" src="https://github.com/user-attachments/assets/5dd65b35-5bc9-4b26-a630-0ba1f161165e" />
Admin landing page with options to:
Add new restaurants
View existing restaurants
7️⃣Show Restaurants (Admin View)
<img width="2151" height="1354" alt="Screenshot 2026-01-04 182620" src="https://github.com/user-attachments/assets/08de7fe9-7cda-4570-a18a-dcfb7a1e042e" />
Admin can view all restaurants with options to:
Update
Delete
View Menu
8️⃣Add Restaurant Page
<img width="2144" height="1308" alt="Screenshot 2026-01-04 182637" src="https://github.com/user-attachments/assets/8e31e6d0-9ae1-4562-8168-e143158c2c88" />
Admin form to add new restaurants by entering:
Name
Image URL
Cuisine
Rating
🔐 Razorpay Payment Gateway (Test Mode)
<img width="2145" height="1271" alt="Screenshot 2026-01-04 183102" src="https://github.com/user-attachments/assets/1ce9bd1d-4bca-4a04-9525-72216347e368" />
This screen shows the secure payment interface integrated using Razorpay.
After clicking “Pay with Razorpay” on the checkout page, users are redirected to this popup.
Key highlights:
Displays complete price summary of the order
Supports multiple payment options:
Debit / Credit Cards
Net Banking
Wallets
Pay Later options
Runs in Razorpay Test Mode for development and testing
Ensures secure and seamless transaction flow
Automatically linked to the logged-in user’s mobile number
