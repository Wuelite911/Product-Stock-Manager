# 📦 Product Management System (WinForms + MySQL)

This project is a simple **Product and Inventory Management System** developed using Windows Forms. It is integrated with a MySQL database and supports basic CRUD operations.

---

## 🚀 Features

- 🧾 Add, update, and delete products
- 🔍 Product search functionality
- 📊 DataGridView-based product listing
- 📂 Category-based filtering
- 📅 Product creation date selection
- 📦 Total product, stock, and value calculations
- 💾 MySQL database integration
- 🧹 Filter reset (Clear functionality)

---

## 🛠️ Technologies Used

- C# (Windows Forms)
- MySQL Database
- MySQL Connector / .NET
- Visual Studio

---

## ⚙️ Installation

1. Clone the repository:
(```bash)
git clone https://github.com/yourusername/your-repo-name.git


---


2. Create the MySQL database:
products table
categories table

---

3. Update the connection string in the project:
   
string connectionString = "server=localhost;database=...;uid=...;pwd=...";

---

4. Open the project in Visual Studio and run it.

---

📊 Database Structure:

Products Table:

ProductID (INT, Primary Key)
ProductName (VARCHAR)
ProductPrice (DECIMAL)
ProductQuantity (INT)
CreatedDate (DATE)
CategoryID (Foreign Key)

Categories Table:

CategoryID (INT, Primary Key)
CategoryName (VARCHAR)

---

📌 Future Improvements
📈 Graphical stock reports and analytics
👤 User authentication system (login/register)
☁️ Cloud database support
🧠 Advanced filtering (price range, date range, etc.)


👨‍💻 Developer Note

This project was developed for learning purposes and will be expanded into a more advanced ERP-style system in the future.
  
---

⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
Contributions are welcome via pull requests.
