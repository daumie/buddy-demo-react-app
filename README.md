# Simple Demo React JS Project

## What is the use of this Repo

This Project is a Simple ReactJS Project which demonstrates the following

1. Creating a Component in React
2. Making HTTP calls
3. Communicating between parent and child component
4. Using Bootstrap along with React
5. Using Basic Routing in React

The project Template can be used to build bigger projects

## Prerequisites

This project was tested on:

- node v11.2.0
- npm  v6.10.3

### Install Node JS

Refer to https://nodejs.org/en/ to install nodejs

## Cloning and Running the Application in local

Clone the project into local

### Running development build

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```bash
npm install
```

In order to run the application Type the following command

```bash
npm start
```

The Application Runs on **localhost:3000**

### Running production build Locally

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```bash
npm install
```

Generate static files for the application with

```bash
npm run build
```

Install [serve](https://www.npmjs.com/package/serve) to serve the static content in the build folder.

```bash
npm install -g serve
```

Serve the application's production build

```bash
serve -i build
```

> N/B 
On a real production environment, you would use a static web server like `Nginx`

## Application design

### Components

1. **Customers** Component : This Component displays a list of customers. This Component gets the data from a json file in assets folder

2. **CustomerDetails** Component : This Component Displays the details of the selected customer. This Component gets its data from a json file in assets folder as well. This Component is the Child Component of *Customers* Component

#### HTTP client

**axios** library is used to make HTTP Calls

#### URL

The application has just one url /customerlist which ties to *Customers* Component

## Resources

**create-react-app** : The following link has all the commands that can be used with create-react-app
https://github.com/facebook/create-react-app

**ReactJS** : Refer to https://reactjs.org/ to understand the concepts of ReactJS

**React Bootstrap** : Refer to https://react-bootstrap.github.io/getting-started/introduction/ to understand how to use React Bootstrap
