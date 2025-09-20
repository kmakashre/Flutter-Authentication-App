# Flutter Authentication App

A complete **user authentication application** built with **Flutter** and **Firebase Authentication**, supporting **login, registration, password reset via email**, and **logout** functionality.

## Features
- **User Registration:** New users can create an account with email and password.  
- **User Login:** Existing users can log in securely.  
- **Password Reset:** Users can reset their password via email.  
- **Logout:** Users can log out and return to the login page.  
- **Welcome Page:** After successful login, users are redirected to a welcome page.  
- **Firebase Integration:** All authentication handled via **Firebase Authentication**.  

## Tech Stack
- **Frontend:** Flutter  
- **Backend/Authentication:** Firebase Authentication  
- **Email Service:** Firebase (for password reset emails)  

## How It Works
1. User opens the app → can choose to **login** or **register**.  
2. **New user registration:** enters email and password → account is created in Firebase.  
3. **Login:** enters credentials → redirected to **welcome page** on success.  
4. **Forgot Password:** clicks reset → email with reset link sent → user clicks link → resets password.  
5. **Logout:** user can log out from welcome page and return to login screen.  

## Future Enhancements
- Add **profile management** (update name, profile picture)  
- Implement **social logins** (Google, Facebook)  
- Enhance **UI/UX** with animations and themes  
- Add **Firebase Firestore** integration to store user details  

