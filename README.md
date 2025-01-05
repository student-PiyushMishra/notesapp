# Express, Node.js, and EJS App

This is a simple web application built using Express, Node.js, and EJS templating engine.

## Prerequisites

Before you begin, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (Recommended version: 14.x or higher)
- [npm](https://www.npmjs.com/) (npm comes with Node.js)

## Getting Started

### 1. Clone the repository

Start by cloning this repository to your local machine:

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies

As `node_modules` is not pushed to GitHub, you need to install the dependencies manually.

Run the following command to install the required packages:

```bash
npm install
```
This will read the package.json and package-lock.json files and install the necessary dependencies.

### 3. Run the application

Once the dependencies are installed, you can run the application with the following command:

```bash
npm start
```

This will start the server, and you should see output similar to:

```arduino
Server is running on http://localhost:3000
```

### 4. Acess the app

Open your browser and go to http://localhost:3000 to view the application.

## Scripts

- `npm start`: Starts the application.
- `npm install`: Installs dependencies from `package.json`.

## Folder Structure

- `views/`: Contains the EJS templates.
- `texts/`: Would contain all of your notes.
- `public/`: Contains the static files like images (not used any in this project), stylesheets and JS files.
- `index.js`: Contains the code for the express app.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.