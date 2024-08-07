# Angular Login.UI Project
[![Angular](https://img.shields.io/badge/Angular-18.1.4-red)](https://angular.dev/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.3-blueviolet)](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
[![MDB Angular](https://img.shields.io/badge/MDB_Angular-5.2.0-yellow)](https://mdbootstrap.com/docs/angular/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

This project demonstrates a simple authentication system using Angular, integrated with a .NET Core backend utilizing JWT (JSON Web Tokens) for secure authentication.

## Technologies Used
- **Angular**: Frontend framework for building single-page applications.
- **Bootstrap 5.3.3**: Frontend component library for responsive and mobile-first design.
- **Angular Material Design Bootstrap (MDB)**: Angular components based on Material Design and Bootstrap for UI elements.
- **JWT (JSON Web Tokens)**: Secure authentication mechanism used between Angular frontend and .NET Core backend.
- **TypeScript**: Programming language used for Angular development.
- **HTML/CSS**: Markup and styling languages for structuring and presenting the frontend UI.
- **Visual Studio Code**: Integrated development environment (IDE) for Angular and TypeScript development.

## Features Implemented
- **Login Component**: Provides a form for users to enter their credentials and authenticate.
- **Authentication Service**: Manages user authentication using JWT tokens.
- **Navbar Component**: Displays a navigation bar with a logout button after successful login.
- **Responsive Design**: Ensured the application is responsive using Bootstrap's grid system.

## Setup Instructions
- To run this project locally:

1. **Clone the repository**:
```bash
  git clone https://github.com/Pedrolustosa/Login.UI
```

```bash
  cd Login.UI
```

3. **Install dependencies**:
```bash
  npm install
```

4. **Run the Angular development server**:
```bash
  ng serve
```

5. **Open the application**:
- Navigate to `http://localhost:4200/` in your web browser.

## Usage
- Access the login page (`/login`) to authenticate with valid credentials.
- After successful login, navigate to the home page (`/home`) where you can view authenticated content.
- Use the logout button in the navbar to securely log out of the application.

## Contributing
Contributions are welcome! Feel free to fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
