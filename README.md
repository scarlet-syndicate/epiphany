# Epiphany - AI Academic Dashboard

## Overview

Welcome to Epiphany, an AI-powered academic dashboard designed to assist students in managing their academics efficiently. Co-led by Greninja and Lance under the organization "Ghosts of War," Epiphany aims to provide students with a seamless interface to track their academic progress, access their syllabus and courses, and get AI-driven assistance for any academic doubts. Additionally, the dashboard keeps students informed about any updates or changes in their courses or syllabus.

## Table of Contents

1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

## Features

- **Academic Tracking**: Monitor your grades, assignments, and progress in real-time.
- **Course Management**: Access detailed information about your courses and syllabus.
- **AI Assistance**: Get instant help with academic doubts using our AI assistant.
- **Notifications**: Receive updates and notifications about any changes in your courses or syllabus.

## Tech Stack

- **Frontend**:

  - [Next.js](https://nextjs.org/) - A React framework for server-side rendering and static web applications.
  - [React](https://reactjs.org/) - A JavaScript library for building user interfaces.

- **Backend**:
  - [Go](https://golang.org/) - A statically typed, compiled programming language designed for backend development.

## Installation

### Prerequisites

- Node.js (version 14 or above)
- Go (version 1.16 or above)
- Git

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/ghosts-of-war/epiphany.git
   cd epiphany
   ```

2. **Frontend Setup**

   ```bash
   cd frontend
   npm install
   npm run dev
   ```

   The frontend will be available at `http://localhost:3000`.

3. **Backend Setup**

   ```bash
   cd backend
   go mod download
   go run main.go
   ```

   The backend will be available at `http://localhost:8080`.

## Usage

1. **Access the Dashboard**

   Open your browser and navigate to `http://localhost:3000`.

2. **Login/Sign Up**

   Use your academic credentials to log in or sign up if you are a new user.

3. **Navigate through the Dashboard**

   - **Home**: Overview of your academic status.
   - **Courses**: List and details of your enrolled courses.
   - **Syllabus**: Access to your course syllabus.
   - **AI Assistant**: Interact with the AI for any academic help.
   - **Notifications**: Stay updated with the latest changes and updates.

## Contributing

We welcome contributions from the community. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

Please ensure that your code adheres to our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions, suggestions, or issues, please reach out to the project maintainers:

- **Greninja**: greninja@ghostsofwar.org
- **Lance**: lance@ghostsofwar.org

You can also open an issue on our [GitHub repository](https://github.com/ghosts-of-war/epiphany/issues).

Thank you for using Epiphany! We hope it enhances your academic journey.

---

_This README was last updated on May 26, 2024. Please check our repository for the latest information and updates._
