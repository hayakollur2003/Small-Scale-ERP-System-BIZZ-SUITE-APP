# Small-Scale-ERP-System-BIZZ-SUITE-PRO-APP-ADVANCED-ERP & BUSINESS-INTELLIGENCE-SYSTEM
This is an Simple ERP System for Small Scale Industries
**BizSuite Pro - Advanced ERP & Business Intelligence System**
BizSuite Pro is a comprehensive, modern, and intuitive Enterprise Resource Planning (ERP) system designed for small to medium-sized businesses. Built with a focus on speed and usability, it centralizes core business operations into a single, real-time web application. From financial tracking and inventory management to invoicing and reporting, BizSuite Pro provides the tools needed to make data-driven decisions.

This project is built using vanilla JavaScript and leverages the power of Google's Firebase for backend services, ensuring a secure, scalable, and real-time user experience without the need for a dedicated server.

➡️ View Live Demo
https://biz-suite-pro.netlify.app/ 

✨ Key Features
BizSuite Pro is packed with features to cover the entire business management lifecycle:

📊 Interactive Dashboard
At-a-Glance KPIs: Instantly view key metrics like Total Revenue, Net Profit, New Customers, and Items Sold.

Visual Charts: Interactive charts for Revenue vs. Expenses and Sales by Category powered by Chart.js.

Low Stock Alerts: Proactively manage inventory with automatic alerts for products running low or out of stock.

Recent Activity Feed: A live feed of the latest sales and expenses.

💰 Finance Management
Transaction Hub: A centralized view of all sales (income) and expenses.

Expense Tracking: Easily add, edit, and delete business expenses with details like category, amount, and date.

Profit Calculation: Automatic calculation of total revenue, expenses, and net profit.

Advanced Filtering: Filter transactions by date range and type (Sale/Expense) to analyze financial performance.

📦 Inventory & Product Management
Full CRUD Operations: Add, view, edit, and delete products with details like SKU, category, cost, and sale price.

Real-Time Stock Tracking: Inventory levels are updated automatically.

Stock Value Analysis: Visualize the total value of your inventory, broken down by category.

Smart Status Indicators: Badges automatically show whether a product is "In Stock," "Low Stock," or "Out of Stock."

📄 Dynamic Invoicing System
Effortless Invoice Creation: Generate professional invoices for any customer directly from the CRM.

Automatic Stock Deduction: When an invoice is finalized, the stock levels for the sold items are automatically decremented.

Real-time Calculations: Subtotals, taxes, and totals are calculated instantly as you add items.

Print & PDF Export: Easily print invoices or download them as high-quality PDF files for record-keeping and emailing.

📈 Comprehensive Reporting Engine
Generate Key Reports: Create detailed reports for Sales, Inventory, Expenses, and Profit-by-Product.

Export Functionality: Export any report to both CSV for spreadsheet analysis and PDF for professional presentation.

🔐 Authentication & Security
Secure User Accounts: Powered by Firebase Authentication for reliable and secure email/password login.

Per-User Data Isolation: All business data is stored securely and is unique to each user account, thanks to Firestore's security rules.

Demo Mode: A one-click demo mode to explore the application's features with pre-loaded sample data.

📸 Screenshots
(Replace this with a screenshot of your application's dashboard. A good screenshot is worth a thousand words!)

🛠️ Tech Stack & Tools
This project was built using a modern, serverless-first approach:

Frontend: HTML5, CSS3, Vanilla JavaScript (ES6+)

Styling: Tailwind CSS - For rapid, utility-first UI development.

Backend & Database: Google Firebase

Firestore: Real-time NoSQL database for all application data.

Firebase Authentication: For secure user management.

Charting: Chart.js - For creating beautiful and interactive data visualizations.

PDF Generation: html2pdf.js - To convert HTML invoice templates into downloadable PDFs.

Icons: Feather Icons - A collection of clean and simple SVG icons.

🚀 Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
You only need a modern web browser and git installed on your machine.

Installation & Setup
Clone the repository:

Bash

git clone https://github.com/your-username/bizsuite-pro.git
cd bizsuite-pro
Set up your Firebase Project:

Go to the Firebase Console and create a new project.

In your new project, go to Project Settings > General.

Under "Your apps," click the web icon (</>) to register a new web app.

Copy the firebaseConfig object provided.

In the index.html file, find the <script> tag at the bottom and replace the placeholder firebaseConfig object with your own:

JavaScript

// In index.html, around line 1100
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_AUTH_DOMAIN",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_STORAGE_BUCKET",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID"
};
Enable Firebase Services:

In the Firebase Console, go to the Authentication section and enable the "Email/Password" sign-in provider.

Go to the Firestore Database section and create a new database in Test mode to get started quickly. (For production, you'll want to configure security rules).

Run the application:

Since this project uses CDN links for all its dependencies, there's no build step required. Simply open the index.html file in your web browser!

💻 Usage
Sign Up: Create a new account using any valid email address.

Login: Sign in with your newly created credentials.

Demo Mode: Alternatively, click the "Demo Mode" button on the login screen to explore the app with pre-populated sample data without needing to create an account.

Demo Email: test@example.com

Demo Password: password123

📄 License
This project is distributed under the **Apache License 2.0**. See the LICENSE file for more information.

👨‍💻 Author
Kolluru Hayagreeva (Haya)

GitHub: @hayakollur2003

LinkedIn: https://www.linkedin.com/in/hayagreevakolluru
