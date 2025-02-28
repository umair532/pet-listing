# Pet Listing Website

This project is a pet listing website where users can search and view details of various pets. It is built using React, React Router, Context API for state management, and Material-UI for styling.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Design Decisions](#design-decisions)
- [Images](#images)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pet-listing.git

2. Navigate to the project directory:

      cd pet-listing

3. To install the dependencies, run:

      npm install

Create a `.env` file in the root directory and add your API base URL:
VITE_API_BASE_URL=http://your-api-url.com

Start the development server:

      npm run dev

The application will be available at [http://localhost:5173/]

## Usage

To use the application, follow these steps:
  
    Open your browser and go to [http://localhost:5173/]
    Use the search form to search for pets by animal type, location, and breed.
    Click on a pet to view its details.

## Project Structure

The project structure is as follows:

- pet-listing/
- ├── public/
- ├── src/
- │   ├── components/
- │   │   ├── ErrorBoundary.jsx
- │   │   ├── PetDetails.jsx
- │   │   ├── PetList.jsx
- │   │   ├── SearchForm.jsx
- │   ├── contexts/
- │   │   ├── PetContext.jsx
- │   ├── services/
- │   │   ├── api.js
- │   ├── App.jsx
- │   ├── index.jsx
- ├── .env
- ├── .eslintrc.json
- ├── package.json
- ├── README.md

Key Components
- ErrorBoundary.jsx: Catches and displays errors.
- PetDetails.jsx: Displays details of a selected pet.
- PetList.jsx: Displays a list of pets.
- SearchForm.jsx: Allows users to search for pets.
- PetContext.jsx: Manages global state using Context API.

Services
- api.js: Contains functions for making API calls to fetch and search pets.

## Design Decisions
- State Management: Used Context API for state management to keep the project simple and avoid the overhead of Redux for this small application.
UI Library: Used Material-UI for a polished and responsive user interface.
- Error Handling: Implemented an ErrorBoundary component to catch and display errors gracefully.
Routing: Used React Router for navigation between different pages.

## Contributing
- Contributions are welcome! Please open an issue or submit a pull request with your changes.

Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Commit your changes (git commit -m 'Add new feature').
- Push to the branch (git push origin feature-branch).
- Open a Pull Request.


## Images
![image](https://github.com/user-attachments/assets/b27b88b8-4019-48b8-aafe-7b3e3ab9be95) ![image](https://github.com/user-attachments/assets/8cd7de44-34c1-4e84-8b8d-c09f24c3f1cd)
![image](https://github.com/user-attachments/assets/6dd06b93-53bb-4ba8-854d-2297ca873fe3) ![image](https://github.com/user-attachments/assets/fc34414d-50a3-43a9-b635-21ee82848898)


## License
This project is licensed under the MIT License.

umair532 and ensures the repository is accessible and the instructions are clear and easy to follow. This README file provides comprehensive instructions on setting up and running the project, along with a detailed project structure and the design decisions made during development.

