# Environment

This stack for this project includes T3, Yarn, Node.js, React, and Material UI.

## Tech Stack

This project uses the full T3 tech stack with Next.js, NextAuth (Discored), and Postgres.

See more information on the T3 [website](https://create.t3.gg/)

## Node.js

Node.js and React are the frameworks of the app.

## Yarn

Yarn is the package manager used to manage dependencies. Use this to install existing or add new APIs.

## MUI

Material UI is a library of React components used for the UI. Read the [docs](https://mui.com/material-ui/getting-started/) for more information.

# Installation Instructions

To Node is required prior to downloading the project.

## Installing Node.js

Follow the instructions on the Node.js [website](https://nodejs.org/en/download/current) to install Node.js.

## Installing Yarn

Open a command console and run the command:

```
npm install --global yarn
```

## Project Directory

Create an empty folder where you want to store your app.

## Install Git

Follow the instructions on [Git](https://git-scm.com/downloads) to download Git.

## Clone the Repository

Open Git Bash and navigate to the folder you created to store the app. Clone the repository using:

```
git clone https://github.com/SnubbullTrouble/whowantsthisdog.git
```

## Install Dependencies

To install the project dependencies, open /whowantsthisdog/ in a command console. Run the command:

```
yarn install
```

# Configuring the Project

Some environment variables are required to build the app.

## Environment Variables

NextAuth requires some information before the project can be built. The required fields are:

```
NEXTAUTH_SECRET=""
NEXTAUTH_URL="http://localhost:3000"

DISCORD_CLIENT_ID=""
DISCORD_CLIENT_SECRET=""
```

Contact Macon Code to inquire about the application information.

# Using the Development Server

The app runs locally on a local server.

## Building the Application

The application has to be built/rebuilt to view it. To build, run the command:

```
yarn build
```

## Start Development Server

To start the development server, run the command:

```
yarn start
```

## Stopping Developement Server

To stop the server, use <kbd>Ctrl</kbd> + <kbd>C</kbd>.
