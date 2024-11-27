## Bookstore E-Commerce Platform with MERN Stack

Project Overview

Team ID: NM2024TMID11564

## Team Members:

Priyanshu Kumar (Backend Developer & Team Lead): Server-side functionalities, API implementation, and data flow management.

Shibendra Narayan Mishra (Frontend Developer): User interface design and reusable UI components.

Vivek Anand (Database Manager & Documentation): Database schema design and efficient data storage.

Ritesh Kumar Dubey (Project Representative): Report handling and representation.


## Purpose

The project aims to create a platform for managing books, enhancing customer accessibility, and streamlining operations for store owners. Key features include:

## Book management

User registration and profiles

Shopping cart and secure checkout

Recommendations and reviews

Admin dashboard with inventory management



---

## Features

User-Centric Features:

Book Management: Add, edit, and categorize books.

Search & Browse: Search books by title/author and filter results.

User Management: Profiles, wish lists, and order history.

Shopping Cart: Add books and proceed with secure payments.


Admin-Centric Features:

Inventory Management: Stock tracking with admin notifications.

Admin Dashboard: Manage users, inventory, and view analytics.


## Additional Features:

Multi-Format Support: Physical and e-books.

Responsive Design: Compatibility across all devices.



---

## Architecture

Frontend

Technologies: React.js, HTML, CSS, JavaScript.

Styling: Tailwind CSS and Bootstrap.


## Backend

Frameworks: Node.js with Express.

Authentication: JWT for secure token-based authentication.

API Design: RESTful services for client-server communication.


## Database

Database: MongoDB with Mongoose for ODM (Object Data Modeling).



---

## Setup Instructions

Prerequisites

Install Node.js and npm.

Install MongoDB.

Install Git for version control.


## Installation

1. Clone the repository:

git clone <repository-link>


2. Navigate to the project directory:

cd Book-Store-NM


3. Install dependencies:

# Frontend  
cd frontend  
npm install  

# Backend  
cd ../backend  
npm install


4. Start the servers:

# Frontend server  
npm start  

# Backend server  
npm start




---

## API Documentation

Authentication

POST /auth/login

Request Body:

{  
  "username": "user123",  
  "password": "securepassword"  
}

Books

GET /books

Fetch all books with optional filters like genre and author.

POST /books (Admin only)

Add new books to inventory.

Orders

POST /orders

Place an order with user and item details.

GET /orders/{orderId}

Retrieve specific order details.


---

## Testing

Types of Testing:

Functional Testing: Verify features like login, search, and checkout.

Unit Testing: Validate individual components (e.g., calculating totals).

Integration Testing: Ensure frontend-backend communication.

Security Testing: Protect sensitive data with tools like OWASP ZAP.


## Tools Used:

Functional and Integration Testing: Selenium, JMeter.

Security Testing: OWASP ZAP for vulnerability assessments.



---

## Known Issues

Search Functionality: Multi-word queries may yield inaccurate results.

Page Loading Speed: Slower for pages with large inventories.

Payment Gateway: Occasional delays during peak hours.

Wishlist Sync: Changes across devices may not reflect immediately.

Browser Compatibility: Minor alignment issues in older browsers.



---

## Future Enhancements

AI-Powered Recommendations: Advanced search and personalized suggestions.

Multi-Language Support: Cater to a global audience.

Dedicated Mobile App: Support offline access and enhanced usability.

Subscription Models: Unlimited e-book access with tiered pricing.

Social Media Integration: Share reviews and wishlists directly to platforms.

Loyalty Programs: Points-based rewards to improve customer retention.




---

Contributions welcome!
Feel free to fork, submit issues, or create pull requests to improve this project.

