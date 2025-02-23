# GUI Product Shop  

![Screenshot](<https://github.com/rachoni/GUI-Product-Shop/blob/main/screenshot.png>)
This project is a **Graphical User Interface (GUI) Product Shop** built with **Python** and **Tkinter**. It allows users to browse and purchase products, while administrators can add new products.  

## **Features**  

✅ **User Authentication** – Login and registration system with password validation.  
✅ **Browse Products** – Displays available products with names, images, and stock count.  
✅ **Purchase Products** – Users can buy products, reducing stock quantity.  
✅ **Add Products (Admin Only)** – Admins can add new products with a name, image, and quantity.  
✅ **Data Persistence** – Stores user credentials, product data, and session information in `.txt` files.  
✅ **Dynamic Image Loading** – Uses **PIL (Pillow)** for product images.  

## **Project Structure**  

📂 **db/** – Stores user data (`users.txt`), product data (`products.txt`), session info (`current_user.txt`), and images (`images/`).  
📜 **canvas.py** – Creates the main application window.  
📜 **helpers.py** – Provides utility functions like screen clearing.  
📜 **authentication.py** – Manages user login, registration, and session handling.  
📜 **products.py** – Handles product management (display, purchase, addition).  
📜 **main.py** – Launches the application.  

## **How to Run the Project?**  

1. **Clone the repository**  
   ```bash
   git clone <repository_url>
   cd <project_folder>
