# React Authentication with Firebase

A multi-page web application developed with React.js and Vite, featuring essential user authentication and profile management functionalities. The app integrates Firebase for secure authentication and user management, providing a seamless experience across multiple pages.

## Features

- **Multi-Page Application**: Includes five key pages - Login, Signup, Forgot Password, Update Profile, and Dashboard.
- **User Authentication**: Secure user login, signup, and profile management using Firebase.
- **State Management**: Managed application state using Context API for efficient data handling.
- **Navigation**: Implemented React Router DOM for smooth page transitions and navigation.
- **Responsive Design**: Built with Bootstrap and React-Bootstrap for a clean, modern, and responsive UI.

## Technologies Used

- **Frontend**: React.js, Vite, Bootstrap, React-Bootstrap
- **Routing**: React Router DOM
- **State Management**: Context API
- **Authentication**: Firebase

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/aboelnasrvip/React_Authentication_With_Firebase.git)
   cd React_Authentication_With_Firebase

2. **Install dependencies:**
   ```bash
   npm install

3. **Create a Firebase project:**
    - **Go to .**: the Firebase Console
    - Create a new project and enable Authentication with Email/Password.
    - Obtain your Firebase configuration and replace the configuration values in the project.


4. **Set up environment variables::**
    - Create a **.env** file in the root of your project and add your Firebase configuration:
   ```bash
   VITE_FIREBASE_API_KEY=your_api_key
   VITE_FIREBASE_PROJECT_ID=your_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   VITE_FIREBASE_APP_ID=your_app_id
   VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain




5. **Run the application:**
   ```bash
   npm run dev


## Usage

- **Signup: Create a new account with a secure registration process.**
- **Login: Access your account using your credentials.**
- **Forgot Password: Reset your password securely via email.**
- **Update Profile: Manage and update your user information.**
- **Dashboard: View your personalized dashboard upon successful login.**
