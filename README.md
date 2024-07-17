# OurSleepKit Privacy Policy Website

Welcome to the OurSleepKit Privacy Policy website. This project is built using the HTML5 Boilerplate template and hosted on Firebase.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Setup and Deployment](#setup-and-deployment)
- [Privacy Policy](#privacy-policy)
- [License](#license)

## Introduction

This project provides the privacy policy for the OurSleepKit application. It is developed using the HTML5 Boilerplate template and deployed on Firebase Hosting.

## Project Structure

The project structure is as follows:

    '''
    privacy-policy-oursleepkit/
    ├── css/
    │ ├── main.css
    │ └── normalize.css
    ├── img/
    │ └── logo.png
    ├── js/
    │ ├── main.js
    │ └── vendor/
    ├── index.html
    ├── 404.html
    └── README.md
    '''

## Setup and Deployment

### Prerequisites

- Node.js and npm installed
- Firebase CLI installed

### Installation

1. Clone the repository or download the project files.
2. Navigate to the project directory.

### Firebase Setup

1. **Install Firebase CLI**:
    ```bash
    npm install -g firebase-tools
    ```

2. **Login to Firebase**:
    ```bash
    firebase login
    ```

3. **Initialize Firebase Project**:
    ```bash
    firebase init
    ```
  - Select "Hosting: Configure and deploy Firebase Hosting sites".
  - Select your Firebase project.
  - Choose the public directory (e.g., `public`).
  - Configure as a single-page app (if applicable).
  - Do not overwrite `index.html` if it exists.

4. **Deploy the site**:
    ```bash
    firebase deploy
    ```

After deployment, Firebase will provide a URL where your privacy policy website is hosted.

## Privacy Policy

The privacy policy for the OurSleepKit application can be found in the `index.html` file. This policy outlines the terms of use, privacy practices, and user obligations related to the OurSleepKit platform.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
