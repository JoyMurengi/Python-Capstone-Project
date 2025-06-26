# Python-Capstone-Project
# MyCrochet Haven

## Project Description  
MyCrochet Haven is a desktop application that allows customers to browse and shop for handmade crochet products. Designed with a clean and intuitive interface, the app provides a virtual storefront experience where buyers can view product details, filter items by category, and manage a shopping cart. It is built using Python, Tkinter for the GUI, and structured with Object-Oriented Programming (OOP) principles.

## Purpose / Problem Solved  
Small crochet businesses often lack structured platforms to display their products, making it hard for buyers to explore available items. MyCrochet Haven solves this by offering a mock e-commerce experience tailored to handcrafted crochet products. It helps customers engage with products more easily and provides a foundation for future e-commerce expansion.

## Planned Features

### 1. Product Browsing
- View available crochet products with name, category, price, and stock
- Filter products by category (e.g., wearables, home décor, accessories)
- View product descriptions and stock availability

### 2. Shopping Cart (Simulated)
- Add products to a shopping cart
- View total price of items in cart
- Remove items from cart
- Confirm a mock checkout and reduce stock accordingly

### 3. Data Handling
- Load product data from `.csv` files
- Update stock levels after checkout
- Save session data (optional stretch goal)

### 4. User Interface (GUI)
- Graphical interface built using Tkinter
- Separate views for product listing, product details, and cart summary
- Functional buttons for actions like add to cart, remove, and checkout

### 5. Program Structure (OOP)
- Use of classes such as `Product`, `CartItem`, `Cart`, and `AppManager`
- Object-Oriented Programming principles applied to separate concerns and manage data
- Methods to encapsulate cart management, product loading, and user interactions

### 6. Additional Functionalities
- Clear/reset cart option
- Exit application functionality
- Error handling for invalid selections or empty stock

## Technologies / Concepts Used
- Python core: functions, classes, loops, dictionaries
- Tkinter: for GUI development
- csv module: for storing and loading product information
- datetime module (optional): to track session activity or order timestamps

## Success Criteria
- Products are successfully loaded from a data file and displayed in the interface
- Buyers can select, add, and remove products from a shopping cart
- Cart total updates correctly and reflects current selections
- Mock checkout reduces inventory and displays confirmation
- Application runs smoothly with a functional, user-friendly interface
- Code is modular and follows OOP practices

## Stretch Goals
- Visualize product popularity using charts
- Add product ratings or user comments
- Include simulated customer login or profile system
- Export printable order summary or cart receipt
- 
