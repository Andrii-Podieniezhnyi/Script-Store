# Script Store

A React SPA that serves as a library of books with the ability to filter by difficulty level.  
Users can view detailed descriptions and advantages of each book in a modal window, and download the PDF version if needed.  
Authentication is implemented via Firebase, but book browsing is publicly accessible.

---

## 📋 Project Description

Script Store is a book library where users can:

- Filter books by difficulty levels: Junior, Middle, Senior, Ninja  
- View detailed descriptions and benefits of each book in a modal window  
- Download PDF files of books stored in Firebase Storage  
- Use a user-friendly interface with support for light and dark themes  
- Authenticate via Google (Firebase Authentication) to gain extended permissions (e.g., content management)

The application is built using React, React Router, and Firebase for the backend.

---

## ⚙️ Technologies and Libraries Used

- React (version 18.x)  
- React Router (HashRouter) — routing configured for GitHub Pages compatibility  
- Context API — global state management for authentication and books  
- Firebase — authentication, realtime database, and file storage (Firebase Storage)  
- Bootstrap — for UI styling  
- SCSS — for organizing styles using the Sass preprocessor  
- CSS — classic CSS files for styling  
- PDF Download — button to download PDF files from Firebase Storage

---

## 🚀 Features

- User authentication via Google (Firebase Authentication)  
- Public access for browsing the list of books  
- Protected routes for additional features (e.g., content management)  
- Light and dark theme switching  
- Viewing book details in a modal window with descriptions and advantages  
- Downloading books in PDF format directly from Firebase Storage  
- Filtering books by difficulty levels: Junior, Middle, Senior, Ninja  
- Responsive design for various screen sizes

---

## 📥 Getting Started

1. Clone the repository:  
   ```
   git clone https://github.com/andrii-podieniezhnyi/Script-Store.git
   ```

2. Install dependencies:  
   ```
   npm install
   ```

3. Start the development server:  
   ```
   npm start
   ```

4. Open your browser and navigate to:  
   ```
   http://localhost:3000
   ```

---

## 🔐 Security and Firebase Rules

- Data in Firebase Realtime Database is publicly readable.  
- Only the project owner (authenticated user with specific UID) can write data.  
- PDF files are stored in Firebase Storage and are accessible for download via direct links.  
- It is recommended to regularly check and maintain Firebase Rules in the Firebase Console for security.


---

## 📝 License

This project is licensed under the MIT License.

