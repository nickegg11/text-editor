# JATE Text Editor App

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
Welcome to JATE, a simple and lightweight text editor app. This app
uses a client-server architecture allowing you to edit your text
files locally and sync them to a database.

## Features
- Local file editing
- Syncs text files to database
- Offline access
- PWA (Progressive Web App)

## Technologies
- Client: HTML, CSS, JS, and Babel for transpiling
- Server: Node.js, Express, and MongoDB for database

## Installation
To run this app locally, follow these steps:
1. Clone the repo
2. `npm install` in both the root and client directories
3. Set up a MongoDB database
4. Rename `.env.example` to `.env` in the root directory and update the
   `DB_URL` variable with your MongoDB connection string.
5. `npm run dev` in both the root and client directories

## Usage
- Using the app is as simple as opening it in your browser and starting
  to edit your text files.
- You can access your saved files and edit them at any time.
- To use offline capabilities, add the app to your home screen.

## Contributing
Contributions are welcome! Please follow these guidelines:
1. Fork the repo
2. Create a new branch
3. Make your changes and commit them
4. Push your branch to your fork
5. Submit a pull request

## License
This project is under the unlicensed license.

## Contact
For any questions or feedback, please contact me on [GitHub](https://github.com/nickeegg11)
