📚 Bookstore Hub – Online Book Shopping Website

A modern responsive bookstore web application built using HTML, CSS, Bootstrap, and JavaScript.
The website allows users to browse books, add them to a cart, and manage their shopping cart using LocalStorage.

Designed as a frontend e-commerce demo project for learning web development and UI design.

🚀 Project Overview

Bookstore Hub provides a simple and interactive online book browsing experience.

Users can:

Browse featured books

Add books to the cart

View cart items

Manage account page

Store cart data using browser LocalStorage

The website uses modern UI design, animations, and responsive layouts to create a smooth shopping experience.

✨ Features
📖 Book Catalog

The homepage displays a collection of featured books including:

Harry Potter

Lord of the Rings

Robin Hood

The Alchemist

Each book includes:

Book cover image

Book title

Price

Add to Cart button

🛒 Shopping Cart System

The cart system is built using JavaScript LocalStorage.

Features include:

Add books to cart

Prevent duplicate items

Cart item counter in the header

Cart page to view selected books

🔍 Search Bar

The website includes a search bar for searching books.

(Current version shows a placeholder alert for future implementation.)

Future improvement:

Book filtering

Dynamic search results

🎨 Modern UI Design

The interface includes:

Responsive Bootstrap 5 layout

Font Awesome icons

AOS animations for scroll effects

Stylish book cards

Smooth hover animations

Background image design

🧩 Technology Stack
Technology	Purpose
HTML5	Page structure
CSS3	Styling and layout
Bootstrap 5	Responsive design
JavaScript	Cart logic
LocalStorage	Store cart items
Font Awesome	Icons
AOS Library	Scroll animations
📂 Project Structure
BOOKSTORE/
│
├── index.html        # Homepage
├── cart.html         # Shopping cart page
├── account.html      # User account page
│
├── book1.jpg         # Book images
├── book2.jpg
├── book3.jpg
└── book4.jpg
⚙️ How to Run the Project
1️⃣ Download or Clone the Repository
git clone https://github.com/yourusername/bookstore-hub.git
2️⃣ Open the Project Folder

Open the folder in VS Code or any code editor.

3️⃣ Run the Website

Simply open:

index.html

in your browser.

Or run using Live Server extension in VS Code.

🛒 Cart System Logic

The cart functionality works using LocalStorage.

Example:

let cart = JSON.parse(localStorage.getItem("cart")) || [];
cart.push({name, img, price});
localStorage.setItem("cart", JSON.stringify(cart));

This allows cart data to persist even after refreshing the page.

🔮 Future Improvements

Possible upgrades for the project:

Real search functionality

Backend integration (Node.js / Django)

User authentication system

Payment gateway integration

Product categories

Wishlist system

Database-based cart system

👨‍💻 Author

Vijay Selvan

📧 Email
vijayvs2341@gmail.com

🐙 GitHub
https://github.com/vijayvs2341

💼 Portfolio
https://github.com/vijayvs2341/Portfolio
