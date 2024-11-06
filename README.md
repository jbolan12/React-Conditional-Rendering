# React-Conditional-Rendering

# Conditional Rendering React App

A simple React application that demonstrates conditional rendering based on a user's login status and the current time. This project showcases how to display components and elements conditionally in React using JavaScript expressions and logic.

## Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Technologies](#technologies)
6. [Scripts](#scripts)
7. [License](#license)

## Overview

The Conditional Rendering App is built using React to display different components based on the user's login status and the current time of the day.

- **Login Check**: If the user is not logged in, the login form is displayed.
- **Time Check**: If the current time is after 12 PM, a message asking "Why are you still working?" is shown to the user.

## Installation

### Prerequisites

- Node.js (version 14 or above)
- npm (version 6 or above)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/jbolan12/React-Conditional-Rendering.git

   Navigate to the project directory:

bash
cd your-repo


**Install the dependencies:**

bash
npm install


**Start the development server:**

bash
npm start
Open http://localhost:3000 in your browser to view the app.

## Usage
**Components**
App: The main component that checks two conditions:

- isLoggedIn: A boolean that determines if the user is logged in.
- currentTime: The current hour of the day, used to conditionally display a message after 12 PM.
- Login: A component that renders a simple login form with fields for a username and password.

- Input: A reusable input component that accepts props for type and placeholder attributes, which are passed from the Login component.

**Conditional Rendering**
The App component uses conditional rendering in two ways:

- Login Form: If the isLoggedIn variable is false, the Login component is rendered.
T- ime-Based Message: If the currentTime is greater than 12 (i.e., after noon), a message "Why are you still working?" is shown.


## Features
- Conditional Rendering: Use JavaScript conditions to render components and elements based on state or time.
- Reusable Input Component: The Input component can be used for multiple input types and placeholders.
- Login Form: Displays a login form with username and password fields when the user is not logged in.


## Technologies
React (v18.3.1)
React-Dom (v18.3.1)


## Scripts
- start: Runs the app in development mode with react-scripts start.
- build: Builds the app for production with react-scripts build.
- test: Runs the test suite with react-scripts test --env=jsdom.
- eject: Ejects the app from Create React App configuration.


## License
This project is licensed under the MIT License.
