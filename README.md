# NOTE-O-PEDIA

![NOTE-O-PEDIA Logo](https://github.com/user-attachments/assets/fe73b0c9-89d2-42de-9b6e-04e664d8d03e)

---

## Overview

**NOTE-O-PEDIA** is a simple, desktop-based note-taking app built with Electron.js. It allows users to write, save, and view notes with a clean and intuitive interface.

---

## Prerequisites

- **Node.js** (v12 or higher): [Download here](https://nodejs.org/)
- **npm** (comes with Node.js) or **yarn** (optional)

---

## Getting Started

### 1. Clone the Repository

Clone the project from GitHub and navigate to the project folder:

```bash
git clone https://github.com/your-username/note-o-pedia.git
cd note-o-pedia

### 2\. Install Dependencies

Use either `npm` or `yarn` to install the necessary dependencies:

bash

Copy code

`npm install
# or
yarn install`

### 3\. Run the App

Start the Electron app with the following command:

bash

Copy code

`npm start
# or
yarn start`

This command will open the **NOTE-O-PEDIA** application in a new Electron window.

* * * * *

Project Structure
-----------------

-   **main.js**: The main process file that manages the Electron app lifecycle and handles saving/loading notes.
-   **index.html**: The main HTML file containing the UI layout.
-   **renderer.js**: The renderer process file for handling UI interactions and communicating with `main.js` via `ipcRenderer`.

* * * * *

Features
--------

-   **Write Notes**: Add a new note in the text area.
-   **Save Notes**: Click "Save" to store notes persistently in a JSON file.
-   **View Notes**: Select a saved note from the list view to load it in the text area.

* * * * *

Troubleshooting
---------------

If you encounter issues:

-   Ensure Node.js is correctly installed (`node -v` to check the version).
-   Confirm that dependencies were installed successfully.
-   Open Developer Tools within the app window (Press `Ctrl+Shift+I` on Windows/Linux or `Cmd+Option+I` on macOS) to view any error logs.

