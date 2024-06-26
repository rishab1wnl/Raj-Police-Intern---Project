# Rajasthan Police Internship Project

[![Angular Badge](https://img.shields.io/badge/Angular-14.2.8-red?logo=angular)](https://angular.io/)
[![HTML5 Badge](https://img.shields.io/badge/HTML5-latest-orange?logo=html5)](https://www.w3.org/html/)
[![CSS Badge](https://img.shields.io/badge/CSS-latest-blue?logo=css3)](https://www.w3.org/Style/CSS/Overview.en.html)
[![TypeScript Badge](https://img.shields.io/badge/TypeScript-latest-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Node.js Badge](https://img.shields.io/badge/Node.js-latest-green?logo=node.js)](https://nodejs.org/)
[![Bootstrap Badge](https://img.shields.io/badge/Bootstrap-5.0-purple?logo=bootstrap)](https://getbootstrap.com/docs/5.0/)

## Project Overview

The **Rajasthan Police Internship Project** is a web application developed to assist with various administrative tasks for the Rajasthan Police. The project utilizes a modern tech stack to create an efficient and user-friendly interface for handling data and operations.

## Technologies Used

- **Frontend:**
  - [Angular](https://angular.io/) for building the dynamic user interface.
  - [HTML5](https://www.w3.org/html/) for the structure of web pages.
  - [CSS](https://www.w3.org/Style/CSS/Overview.en.html) for styling web pages.
  - [TypeScript](https://www.typescriptlang.org/) for adding static typing to JavaScript.
  - [Bootstrap](https://getbootstrap.com/docs/5.0/) for responsive UI components.
  - [ngx-toastr](https://www.npmjs.com/package/ngx-toastr) for displaying notifications.

- **Backend:**
  - [Node.js](https://nodejs.org/) for server-side scripting.
  - [JSON Server](https://www.npmjs.com/package/json-server) for creating a REST API.

- **Other Tools and Libraries:**
  - [Git](https://git-scm.com/) for version control.
  - [Lordicon](https://lordicon.com/) for animated icons.
  - [favicon](https://favicon.io/) for browser tab icon.
  - [HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP) for communication protocol.

## Project Structure
```
Here's a detailed breakdown of the project structure:
Rajasthan-Police-Intern-Project/
│
├── README.md               # Project documentation
├── package.json            # Project dependencies and scripts
├── angular.json            # Angular CLI configuration
├── tsconfig.json           # TypeScript configuration
│
├── src/
│   ├── app/
│   │   ├── components/     # Reusable components (header, footer, forms, etc.)
│   │   ├── services/       # Business logic and data handling services
│   │   ├── models/         # TypeScript interfaces and models
│   │   ├── modules/        # Custom Angular modules
│   │   ├── ...             # Additional application files
│   │
│   ├── assets/             # Static assets (images, icons, fonts)
│   ├── environments/       # Environment configurations (dev, prod)
│   ├── index.html          # Main HTML file
│   ├── main.ts             # Main entry point for Angular
│   ├── styles.css          # Global styles
│   ├── ...                 # Additional source files
│
├── .gitignore              # Files and directories to ignore in Git
├── karma.conf.js           # Karma test runner configuration
├── protractor.conf.js      # Protractor end-to-end test configuration
└── ...

```


## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/)
- [Angular CLI](https://angular.io/cli)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/rishab1wnl/Raj-Police-Intern-Project.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Raj-Police-Intern-Project
    ```
3. **Install the dependencies:**
    ```bash
    npm install
    ```

### Running the Application

1. **Start the Angular development server:**
    ```bash
    ng serve
    ```
    The application will be accessible at [http://localhost:4200/](http://localhost:4200/).

2. **Start the JSON server for API:**
    ```bash
    npm run json-server
    ```
    The API will be accessible at [http://localhost:3000/](http://localhost:3000/).

### Useful Commands

- **Build the project:**
    ```bash
    ng build
    ```
- **Run unit tests:**
    ```bash
    ng test
    ```
- **Run end-to-end tests:**
    ```bash
    ng e2e
    ```

## API Endpoints

- **User Login:** `http://localhost:3000/login`
- **User Signup:** `http://localhost:3000/sign-up`
- **Expense Data:** `http://localhost:3000/expensedata`

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please see the [contribution guidelines](CONTRIBUTING.md) for more information.

## Contact

For any questions or inquiries, please contact the project maintainers.

**Let’s make this project better together!**
