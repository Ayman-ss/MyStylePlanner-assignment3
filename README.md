>  MyStyle Planner  
A personal wardrobe & shopping planner web app 
MyStyle Planner is a full-stack web application designed to help users track items they want to buy, categorize them, prioritize them, and keep notes, basically replacing the “random screenshots” habit with something more organized.  
This project was built as Assignment 3 and includes full CRUD functionality and user authentication.

---

>>  Features

>>>  User Authentication
- Sign up
- Sign in

>>>  CRUD for Planner Items
Users can:
- Create items  
- Read all items in a clean card layout  
- Update item details  
- Delete items with a confirmation modal  

Each item stores:
- Name  
- Store  
- Category  
- Price  
- Priority (Low / Medium / High)  
- Status (Wishlist or Purchased)  
- Notes  

>>> MongoDB Integration
- Items and users stored in MongoDB Atlas
- Mongoose used for schemas & operations

>>> Responsive UI
- Custom CSS theme (neutral beige + deep  red)
- Clean layout inspired by magazine-style shopping planners  
- Fully responsive for laptop screens

---

>>  Technologies Used

>>> Database
- MongoDB Atlas  
- Mongoose ORM  

>>> Tools
- Visual Studio Code  
- Git & GitHub  
- Render (for deployment)  
- MongoDB Compass ( though Atlas was used primarily)

---

>>  Course Materials Used (INFR3120)

The following concepts from the course that I used:

>>> Module 1: Express Setup  
- Setting up Express server  
- Routing with `express.Router()`  
- Using EJS view engine  

>>>  Module 2: MongoDB & Mongoose  
- Connecting to MongoDB Atlas  
- Using schemas  
- CRUD operations

>>> Module 3: RESTful CRUD  
- GET/POST routes  
- Edit & Delete patterns  
- Delete confirmation view  

>>> Module 4: Authentication  
- Sign up & login forms  
- Password hashing  
- Sessions with express-session  
- Protecting routes (middleware)  

>>> Module 5: Deployment  
- Deploying to Render  
- Using environment variables  
- Hiding credentials with `.env` and `.gitignore`

---

Author
Ayman Sohail
Ontario Tech University
B.I.T. Networking & IT Security
