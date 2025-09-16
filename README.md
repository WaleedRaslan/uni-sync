# 🛍️ Uni Sync – E-commerce Application
### A responsive E-commerce application uisng flutter integrated with firebase console to store data like products, users, orders, and shipping status and Authentication for users.

# Main Features
### 1) Mobile App
- #### 🛒 Browse products by categories

- #### ➕ Add products to shopping cart

- #### 💵 Place orders (Cash on Delivery for now)

- #### 🚚 Track order status (Processing → Shipped → Delivered)

- #### 📜 View order history

- #### 👤 Manage account/profile

- #### 🔐 User authentication (Login/Signup) via Firebase Authentication

- #### ☁️ Store product, user, and order data using Firebase Firestore

- #### 🖼️ Upload and display product images and order invoices using Firebase Storage 

### 2) Adminin Dashboard
- 

# Demo
- ### [Click Here..!](https://www.linkedin.com/posts/waleed-raslan-027a57318_flutter-dart-firebase-activity-7373202321637560320-ioNn?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFCZ_F8B7ajEsIeOhVGqIQpC1Vuo1MznIPk)

# Project Screen Shots
- ### [Login Screen](https://i.ibb.co/B2T9SydP/Android-Emulator-Pixel-6-5554-9-16-2025-7-52-47-AM.png)

- ### [Get Satrted Screen](https://i.ibb.co/3YQTm2Lg/Android-Emulator-Pixel-6-5554-9-16-2025-7-52-50-AM.png)

- ### [Location Screen](https://i.ibb.co/pVxSR0Z/Android-Emulator-Pixel-6-5554-9-16-2025-7-54-02-AM.png)

- ### [Home Screen](https://i.ibb.co/Vp5GVKd4/Android-Emulator-Pixel-6-5554-9-16-2025-7-53-46-AM.png)

- ### [Product Details Screen](https://i.ibb.co/fdh9DG35/Android-Emulator-Pixel-6-5554-9-16-2025-7-54-59-AM.png)

- ### [User Cart Screen](https://i.ibb.co/NdgPX5Nm/Android-Emulator-Pixel-6-5554-9-16-2025-7-53-54-AM.png)

- ### [Order Status Screen](https://i.ibb.co/YFW6nSMj/Android-Emulator-Pixel-6-5554-9-16-2025-7-54-14-AM.png)

# Installation
``` bash
   git clone https://github.com/WaleedRaslan/uni-sync.git
   cd project
``` 

# Project Structure
``` bash
Uni-Sync/
│
├── customer_app/                 # Flutter customer mobile app (Android & iOS)
│   ├── lib/                       # Dart source code
│   ├── assets/                    # Images, icons, and other static assets
│   ├── android/                   # Android-specific files
│   ├── ios/                       # iOS-specific files
│   ├── pubspec.yaml               # Flutter dependencies and metadata
│   └── README.md
│
├── admin_dashboard/               # C#.NET Windows Forms admin app
│   ├── UniSyncAdmin.sln           # Visual Studio solution file
│   ├── UniSyncAdmin/               # Project source code (forms, classes, logic)
│   └── README.md
│
├── .gitignore
└── README.md                      # Main documentation
```
# Data Storage

### Firebase Services Used

- #### Firebase Firestore (Database)

- #### Stores all application data such as:

- #### Products (name, price, image URL, description, category)

- #### Users (profile info, email, password hash)

- #### Orders (items, total price, user reference, timestamps)

- #### Order shipping status (Processing → Shipped → Delivered)

### Firebase Authentication

- #### Handles user registration and login (email & password)

- #### Used by the Customer App to authenticate users

- #### Firebase Storage

- #### Stores uploaded media such as:

- #### Product images (uploaded by admin)

- #### Order invoices (optional, uploaded by admin)

- #### Firebase Cloud Messaging (FCM)

- #### Sends push notifications to customers about:

- #### Order status updates
