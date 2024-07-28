# dashboard-demo-app
 It's a Dashboard built-in React+Vite.

![Screenshot 2024-07-28 134035](https://github.com/user-attachments/assets/51dcf0ae-7088-483c-853f-0f2c16d16476)

Description
This is a React project bootstrapped with Vite. The project includes a Sidebar and Content layout, utilizing a context provider for managing the sidebar state.

Installation
Clone the repository

sh
Copy code
git clone (https://github.com/villain5268/dashboard-demo-app)
cd your-repository-name
Install dependencies

sh
Copy code
npm install
Available Scripts
In the project directory, you can run:

npm run dev
Runs the app in development mode.
Open http://localhost:5173 to view it in the browser.

The page will reload if you make edits.

npm run build
Builds the app for production to the dist folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

npm run preview
Preview the production build locally.

npm run lint
Runs the linter to check for code issues.

Project Structure
React+Vite
Copy code

your-repository-name/
├── public/
│   ├── favicon.ico
│   └── ...
├── src/
│   ├── components/
│   │   ├── Cards/
│   │   │   └── Cards.jsx
│   │   ├── Transactions/
│   │   │   └── Transactions.jsx
│   │   ├── Report/
│   │   │   └── Report.jsx
│   │   ├── Budget/
│   │   │   └── Budget.jsx
│   │   ├── Subscriptions/
│   │   │   └── Subscriptions.jsx
│   │   ├── Savings/
│   │   │   └── Savings.jsx
│   │   ├── Loans/
│   │   │   └── Loans.jsx
│   │   └── Financial/
│   │       └── Financial.jsx
│   ├── context/
│   │   └── sidebarContext.jsx
│   ├── data/
│   │   └── data.js
│   ├── layout/
│   │   ├── sidebar/
│   │   │   └── Sidebar.jsx
│   │   └── content/
│   │       └── Content.jsx
│   ├── utils/
│   │   └── images.js
│   ├── App.css
│   ├── App.jsx
│   ├── ContentTop.css
│   ├── ContentMain.css
│   ├── Sidebar.css
│   └── index.css
├── .gitignore
├── index.html
├── package.json
├── README.md
└── vite.config.js

Dependencies
React
ReactDOM
Vite
