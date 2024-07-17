
# Quiz Application

Live Demo : https://quiz-application-bice-eta.vercel.app/

This repository contains a Quiz Application built using React. The application provides an interactive quiz experience with background music to enhance the user experience.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Assets](#assets)
- [Running the Application](#running-the-application)
- [License](#license)

## Installation

Before running the application, ensure you have the following installed on your machine:

- Node.js
- Yarn

Clone the repository and install the dependencies:

```bash
git clone https://github.com/your-username/quiz-application.git
cd quiz-application
yarn install
```

## Usage

To start the application, use the following command:

```bash
yarn start
```

This will run the application in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Project Structure

The project has the following structure:

```
quiz-application/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── assets/
│   │   ├── bg.jpg
│   │   ├── correct.mp3
│   │   └── play.mp3
│   │   └── wrong.mp3
|   |── components/
|   |   |── Start.jsx
|   |   |── Timer.jsx
|   |   |── Trivia.jsx  
│   ├── App.css
│   ├── App.jsx
│   ├── index.js
│   └── ...
├── .gitignore
├── package.json
├── README.md
└── yarn.lock
```

### src

- **App.jsx**: The main component of the application.
- **App.css**: Styling for the application.
- **index.js**: The entry point of the React application.

### public

- **index.html**: The main HTML file that is served by the React application.

### assets

- **bg.jpg, play.mp3, correct.mp3, wrong.mp3**: Background music files and images used in the application.

## Running the Application

To run the application, use the following command:

```bash
yarn start
```

This will start the development server and you can view the application by navigating to [http://localhost:3000](http://localhost:3000) in your web browser.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
