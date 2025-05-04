# 💡 React Lights Out

> A React puzzle game where you click cells to turn off all the lights. Clicking a cell toggles it and its orthogonal neighbors.

[![React](https://img.shields.io/badge/react-18%2B-blue)](https://reactjs.org/)

---

## 📋 Table of Contents

1. [About](#about)  
2. [Features](#features)  
3. [Tech Stack](#tech-stack)  
4. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
5. [Usage](#usage)  
6. [Further Study](#further-study)  
7. [Testing](#testing)  
8. [Contact](#contact)  

---

## 🌟 About

**Lights Out** is a classic logic puzzle on a grid of lights. Clicking any cell toggles that light plus its immediate neighbors (up, down, left, right). The goal is to turn all lights off.

This assignment focuses on managing shared state and event handlers across components:

- **App** renders the **Board**.  
- **Board** holds the 2D array of booleans and all flip logic.  
- **Cell** displays an individual light and invokes a callback when clicked.  

When all lights are off, the board is replaced by a “You Won!” message.

---

## ✨ Features

- **Dynamic Grid**: Configurable number of rows and columns.  
- **Toggle Logic**: Click flips the target cell and its neighbors.  
- **Win Detection**: Automatically shows a “You Won!” message when all lights are off.  
---

## 🛠 Tech Stack

- **Framework:** React 18+ (functional components)  
- **State Management:** `useState` in **Board**  
- **Event Handling:** Click handlers passed from **Board** to **Cell**  
- **Styling:** CSS
- **Build Tool:** Create React App or Vite  

---

## 🏁 Getting Started

### Prerequisites

- Node.js v14 or higher  
- npm (bundled with Node.js) or Yarn  

### Installation

```bash
# 1. Clone the repo
git clone https://github.com/malmonte827/react-lights-out.git
cd react-lights-out

# 2. Install dependencies
npm install
# or
yarn

# 3. Start the development server
npm start
# or
yarn start
```
---
### 📖 Usage

1. Play: Click any cell to toggle it and adjacent cells.

2. Objective: Turn off all lights.

3. Win: When no lights remain, a “You Won!” message appears.
---
### 🧪 Testing

- Component Tests: Smoke and snapshot tests for App, Board, and Cell.

- Logic Tests:

    -  Verify that clicking a cell toggles the correct neighbors.

     -   Confirm win detection when all lights are off.

     -  Simulate a full game sequence in a test.
    
```bash
npm test
# or
yarn test
```
## Contributing

We welcome contributions! To contribute:

- Fork the repository

- Create a new branch (git checkout -b feature-name)

- Commit your changes (git commit -m 'Add new feature')

- Push to the branch (git push origin feature-name)

- Open a pull request

## Contact

For questions or suggestions, reach out:

- Email: malmonte827@gmail.com
