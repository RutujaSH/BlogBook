# 📖 BlogBook  
**Blog Management Website using Node.js, Express, MongoDB, and EJS**  
---

A full-stack **Blog Application** where users can **create, read, comment, and manage blogs**.  
Built with **Express.js, MongoDB, EJS, and JWT authentication**, it provides a smooth blogging experience with **user authentication, comments, and blog management**.  

---

## 🔑 Key Features  

### 👤 User Management  
- 🔒 **User Signup & Login** (JWT Authentication)  
- Profile-based secure access  
- Only logged-in users can **create, delete, and manage blogs**  

### 📰 Blog Management  
- View **all blogs** on homepage as cards
- Open **single blog page** with content, image, author, and body text  
- ✍️ Create new blogs with **title, image, and content**  
- ❌ Delete blogs (only by author)  

### 💬 Comments Section  
- Add comments on blogs  
- Each comment shows **commenter name + message**  

---

## 🛠️ Tech Stack  

- **Backend:** Node.js, Express.js  
- **Templating Engine:** EJS  
- **Database:** MongoDB (Mongoose)  
- **Authentication:** JSON Web Token (JWT)  
- **File Uploads:** Multer  
- **Environment Config:** Dotenv  
- **Cookies Handling:** Cookie-Parser  

---
## 🔑 Example Features in Action  

- **Homepage:** Displays all blogs as cards  
- **Click on Blog:** Opens full blog with content, image, author, and comments  
- **Login:** Secure JWT-based authentication  
- **Add Blog:** Upload image + add blog content with title & body  
- **Comments:** Add your thoughts under blogs  
- **Delete Blog:** Blog owner can remove their blog  

---

## 🌐 Deployment website url 

### https://blogbook-ghw3.onrender.com/

---

## 📂 Project Structure

```bash
BlogBook/
│── models/        # Mongoose schemas (User, Blog, Comment)  
│── routes/        # Express routes (auth, blogs, comments)  
│── views/         # EJS templates  
│── public/        # Static files (images, CSS, uploads)
│── services/      # Needed services (authentication logics)
│── app.js         # Main server file  
│── .env           # Environment variables  

```
---
## 🚀 Getting Started  

### Clone the repo  
```bash
git clone https://github.com/RutujaSHBlogBook.git
cd BlogBook
```

### Install dependencies

```bash
npm install
```

###Run the server

```bash
npm start
```
-By default, the app runs on http://localhost:8000

---

#### And here you are ready to go...
---
### Keep learning! Keep Exploring!


