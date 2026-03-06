# PopX Mobile Authentication Interface

A **pixel-perfect mobile authentication interface** built using **React**, featuring a clean UI, smooth navigation, and a centered mobile layout.  
This project demonstrates modern **frontend development best practices**, focusing on usability, accessibility, and responsive UI design.

---

## Live Demo

🌐 **Website:**  
https://melodious-madeleine-27d7cf.netlify.app/

💻 **GitHub Repository:**  
https://github.com/BHIRAVLOKESH/PopX-task

---

# Application Screens

## Welcome Screen
![Welcome Screen](assets/welcome.png)

---

## Create Account Screen
![Register Screen](assets/register.png)

---

## Login Screen
![Login Screen](assets/login.png)

---

## Account Settings Screen
![Account Screen](assets/account.png)

---

## Tech Stack

- **React (Vite)**
- **Tailwind CSS**
- **React Router DOM**
- **JavaScript (ES6+)**
- **HTML5**
- **CSS3**

---

## Features

- Pixel-perfect UI implementation based on the provided design
- Mobile-first layout with a centered app container
- Floating input labels inspired by the PopX style
- Clean and reusable form components
- Client-side validation
- Proper button and link semantics
- Seamless page navigation without reloads
- Responsive and accessible UI design

---

## Authentication Flow

Create Account → Account Settings  
Login → Account Settings  

For demonstration purposes, authentication is **simulated on the client side** without backend integration.

---

## Validation

Basic client-side validation is implemented using:

- Native HTML attributes such as `required` and `minLength`
- Simple state-based checks to enable or disable submit buttons

This keeps the code **clean while improving the user experience**.

---

## Project Structure

```
src/
├── assets/
├── pages/
│   ├── Welcome.jsx
│   ├── Register.jsx
│   ├── Login.jsx
│   └── Account.jsx
├── routes/
│   └── AppRoutes.jsx
├── App.jsx
└── main.jsx
```

---

## Author

**Bhirav Lokesh**

GitHub:  
https://github.com/BHIRAVLOKESH
