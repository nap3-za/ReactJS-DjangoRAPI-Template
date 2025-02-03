# React Frontend

## Overview
This is a React.js template designed to work seamlessly with a Django REST Framework (DRF) backend. It includes preconfigured technologies and features to accelerate API development.

## Features
- **Vite + React + TypeScript**
- **Tailwind CSS** for styling
- **Redux Toolkit** for state management
- **Pre-configured API Endpoints** using `AppEndpoints.jsx`
- **Modular Routing** in `AppRoutes.jsx`
- **Global Constants** in `Constants.jsx`
- **Utility Functions** in `Utilities.js`

## Folder Structure
```
react_app/
│── src/
│   ├── App.tsx
│   ├── main.tsx
│   ├── AppEndpoints.jsx  # API endpoint configurations
│   ├── AppRoutes.jsx      # Routing structure
│   ├── AppUrls.jsx        # API URL management
│   ├── Constants.jsx      # Global constants
│   ├── FieldChoices.jsx   # Field value mappings
│   ├── Utilities.js       # Helper functions
│   ├── assets/            # Static assets
│   ├── components/        # Reusable UI components
│   ├── pages/             # Page-level components
│   ├── reduxApp/          # Redux state management
│── tailwind.config.js      # Tailwind CSS configuration
│── vite.config.ts          # Vite configuration
│── tsconfig.json           # TypeScript configuration
│── package.json            # Dependencies
```

## Pages Directory
The `pages` directory contains key sections of the application, where the main functionality is implemented.
- **account/**: Manages user account-related functionalities such as profile settings and preferences.
- **authentication/**: Handles user authentication, including login, signup, and password reset features.
- **misc/**: Contains miscellaneous pages that do not fit into the other categories, such as custom static pages or additional UI components.

## Installation & Setup
```sh
# Install dependencies
yarn install

# Run the development server
yarn dev

# Set application name in `src/Constants.jsx`
...BRAND_NAME_NORMAL = 
...BRAND_NAME_LOWER = 
```