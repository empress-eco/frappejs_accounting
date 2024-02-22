<div align="center">
  ![Empress EmpressJS + Accounting Logo](https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png
</div>

Welcome to the Empress EmpressJS + Accounting project, your go-to solution for effortlessly setting up and developing applications based on the robust EmpressJS framework. Our focus here is to provide a seamless experience for developing the Accounting application.

- [Explore Detailed Documentation](https://grow.empress.eco/)
- [Report Bugs](https://github.com/empress-eco/Empressjs_accounting/issues)
- [Request Features](https://github.com/empress-eco/Empressjs_accounting/issues/new)

## About The Project

### 📖 Overview
Empress EmpressJS + Accounting serves as a parent repository designed to streamline the app development process using the EmpressJS framework. It employs Yarn Workspaces and a Monorepo workflow to enhance your development experience, making it smoother and more efficient.

### 🌟 Key Features
- Hassle-free setup for EmpressJS development environment.
- Simplified development process with Yarn Workspaces and Monorepo workflow.
- User-friendly installation and setup process.

### 🎯 Target Audience
This project is geared towards developers looking for a simplified and efficient workflow when building applications with the EmpressJS framework.

### 🛠 Built With
- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)

## Technical Stack and Setup Instructions

### Prerequisites
Ensure you have the build essentials installed on your system. For Ubuntu, you can install these using the following command:

```bash
apt-get install build-essential python git
apt-get install libgconf-2-4
```

### Installation
Follow these steps to setup your development environment:

1. Install [Node.js](https://nodejs.org/en/) LTS (version 8.11.1). Tip: It's best to install and manage Node with [nvm](https://github.com/creationix/nvm).
2. Install `yarn` package manager.

```bash
npm install -g yarn
```
3. Clone this repo

```bash
git clone --recurse-submodules https://github.com/empress-eco/Empressjs_accounting.git
```
4. Install dependencies and launch Accounting

```bash
cd Empressjs_accounting

# Install dependencies
yarn

# Start Empressjs server
yarn start
```

Upon running `yarn start`, a Node server will start on http://localhost:8000, which will also handle bundling of assets using webpack middleware.

## Usage
After setting up your environment, you can start developing your applications. If you're building an accounting app, simply load the app on your browser by visiting http://localhost:8000.

## Contribution Guidelines
We value your contributions! To contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgements

### License
This project is under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgements
Our heartfelt gratitude goes to the Empress Community, who provided the EmpressJS framework and the Accounting application repository. Their innovativeness and dedication have been instrumental in making our work easier. Special thanks to Empress Technologies for their valuable contributions that have significantly simplified the development process.