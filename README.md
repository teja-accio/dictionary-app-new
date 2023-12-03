# Frontend-4-Module-Test--Nov

# React Dictionary App



![React Dictionary App](app-<img width="959" alt="Dict" src="https://github.com/soumya898/Frontend-4-Module-Test--September/assets/109026120/a4469225-b445-43b7-99f7-73bc588e6d2a">
screenshot.png)

This is a React application integrated with Redux for state management that allows users to search for word definitions, view their search history, and see detailed explanations for individual words. The application follows the provided UI design.

## Table of Contents

- [Features](#features)
- [API](#api)
- [Project Structure](#project-structure)
- [Redux Integration](#redux-integration)
- [UI Implementation](#ui-implementation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Features

### Home Page

- **Navbar**: Displaying the application title and navigation links to Home and History pages.
- **Search Functionality**: Provide an input field where users can type in a word and a button to initiate the search. Display the results below the input.

### History Page

- **Display**: A list of previously searched words.
- **Storage**: History should be stored and managed in the Redux store.
- **Redirection**: Clicking on a word in the history list should redirect users to the word's details page.

### Word Details Page

- **Display**: Detailed information of a word. This includes its phonetics, meanings, part of speech, definitions, and audio pronunciations.
- **Dynamic Routing**: Use dynamic routing to handle different words (`/word/:word`).

### Loader

- **Display**: A visually appealing loader/spinner while fetching data from the API.

---

## API

The application uses the DictionaryAPI for fetching word details. You can access the API at [DictionaryAPI](https://api.dictionaryapi.dev/api/v2/entries/en/{word}).

---

## Project Structure

The project is structured as follows:

- `src/`
  - `components/`: React components for the application.
  - `redux/`: Redux store, actions, and reducers.
  - `routes/`: React Router routes for different pages.
  - `styles/`: CSS styles for the application.
  - `utils/`: Utility functions.
  - `App.js`: Main application component.
  - `index.js`: Entry point of the application.

---

## Redux Integration

Redux is used for state management in the application. The Redux setup includes actions and reducers to manage the history of searched words. Redux middleware, like `redux-thunk`, is used for asynchronous operations when fetching data from the API.

---

## UI Implementation

The application's user interface (UI) is implemented to match the provided Figma design. It is designed to be responsive and user-friendly.

---

## Getting Started

To run the application locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/react-dictionary-app.git
   ```
