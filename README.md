# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# WorldWise Travel List App

WorldWise is a travel list application where users can add locations and save their travel plans. The app allows users to click and fetch location details via a fake API.

## Features
- Add any location to your travel list.
- Save and manage your travel plans.
- Fetch location details via a fake API.

## Tech Stack
- **Frontend:** React + Vite
- **Database:** JSON file (used for storing travel data)

## Installation and Setup
Follow these steps to install and run the project locally:

### 1. Clone the Repository
```sh
git clone https://github.com/your-username/worldwise-travel.git
cd worldwise-travel
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Run the Development Server
```sh
npm run dev
```
This will start the frontend development server.

### 4. Start the Fake API Server
```sh
npm run server
```
The fake API will be hosted at:
```
http://localhost:7000
```

## Usage
1. Open the app in your browser (default: `http://localhost:5173` if using Vite).
2. Add new locations to your travel list.
3. Click on a location to fetch details from the fake API.

## Contributing
Feel free to fork the repository and submit pull requests!



