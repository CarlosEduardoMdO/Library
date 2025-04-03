# **Library Management System**  

📚 **A simple web app to manage your book collection**  

## **Overview**  
This project is a **Library Management System** built with HTML, CSS, and JavaScript. It allows users to:  
- **Add** new books with details like title, author, pages, and read status.  
- **Display** books in an organized layout (cards or table).  
- **Remove** books from the library.  
- **Toggle** the read status of each book.  

All book data is stored in an array, ensuring **separation between data logic and UI rendering** for better maintainability.  

---

## **Features**  
✔ **Book Constructor** – Creates book objects with unique IDs (`crypto.randomUUID()`).  
✔ **Add Books** – Submit form entries to dynamically add books to the library.  
✔ **Display Books** – Loop through the array and render books in a clean UI.  
✔ **Remove Books** – Delete books by their unique ID.  
✔ **Toggle Read Status** – Update whether a book has been read or not.  
✔ **Form Handling** – Prevents default submission using `event.preventDefault()`.  

---

## **Setup & Usage**  
1. **Clone the repo**  
   ```bash
   git clone https://github.com/CarlosEduardoMdO/Library.git
   cd Library
   ```

2. **Open `index.html` in a browser**  

3. **Add a book**  
   - Click **"New Book"**.  
   - Fill in details (title, author, pages, read status).  
   - Submit to see it appear in your library!  

4. **Manage books**  
   - **Delete** a book by clicking the remove button.  
   - **Toggle read status** with the "Read/Unread" button.  

---

## **Technical Notes**  
🔹 **Unique IDs** – Each book gets a stable `id` via `crypto.randomUUID()`.  
🔹 **Separation of Concerns** – Data logic (`myLibrary`) is separate from rendering (`renderBooks()`).  
🔹 **Form Handling** – `event.preventDefault()` prevents unwanted page reloads.  

---

## **Future Improvements**  
- **LocalStorage** – Persist books between sessions.  
- **Search/Filter** – Find books by title/author.  
- **Responsive Design** – Better mobile support.  

---

🚀 **Happy Reading!**  
Feel free to contribute or open issues for suggestions.  

📌 **Live Demo:** [GitHub Pages Link](#) *(if deployed)*