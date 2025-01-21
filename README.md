
# AI Cover Letter Assistant

Cover Letter Assistant is a React Native application designed to help users create personalized cover letters efficiently using AI.

## Table of Contents

- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [Installation Steps](#installation-steps)
- [Running the Application](#running-the-application)

## Project Structure

The project's structure is organized as follows:

```
cover-letter-assistant/
├── assets/             # Images, fonts, and other static assets
├── components/         # Reusable React components
├── screens/            # Screen components corresponding to different app views
├── navigation/         # Navigation configuration and navigators
├── services/           # External services and API handlers
├── utils/              # Utility functions and helpers
├── App.js              # Entry point of the application
├── package.json        # Project metadata and dependencies
└── README.md           # Project documentation
```

## Setup Instructions

### Prerequisites

Before setting up the project, ensure you have the following installed:

- **Node.js**: Version 14 or higher. You can download it from [nodejs.org](https://nodejs.org/).
- **npm**: Comes with Node.js. Alternatively, you can use [Yarn](https://yarnpkg.com/) as a package manager.
- **React Native CLI**: Install globally using npm:

  ```bash
  npm install -g react-native-cli
  ```

### Installation Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/idhanwal/cover-letter-assistant.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd cover-letter-assistant
   ```

3. **Install Dependencies**:

   Using npm:

   ```bash
   npm install
   ```

   Or, if you're using Yarn:

   ```bash
   yarn install
   ```

## Running the Application

To start the application on an emulator or a physical device:

- For **iOS**:

  ```bash
  npx react-native run-ios
  ```

- For **Android**:

  ```bash
  npx react-native run-android
  ```

Ensure that your development environment is properly configured for React Native. For detailed setup instructions, refer to the official React Native documentation: [Setting up the development environment](https://reactnative.dev/docs/environment-setup).

---

By following these steps, you should be able to set up and run the Cover Letter Assistant application successfully.
