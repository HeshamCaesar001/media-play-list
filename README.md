# MediaPlaylist

MediaPlaylist is a React application that demonstrates the integration of Redux and Redux Toolkit for state management. The app allows users to manage two separate lists one for movies and another for songs. Users can add items to these lists, remove individual items, or reset both lists entirely.

## Project Overview

This project showcases the use of Redux and Redux Toolkit in a React.js application. It includes two main components: `MovieList` and `SongsList`, each responsible for displaying and managing their respective media lists. The project structure emphasizes the use of Redux slices for managing state and actions, demonstrating how to effectively connect Redux with React components.

## Features

- **Add Movies and Songs**: Users can add movies or songs to their respective lists.
- **Remove Items**: Each item in the list has an associated remove button, allowing users to delete individual movies or songs from the list.
- **Reset Lists**: A reset button is provided to clear both the movies and songs lists simultaneously.
- **State Management**: The application utilizes Redux for managing the state of the lists, with slices for movies and songs.

## Project Structure

The project is organized into the following directories within the `src` folder:

- **components**: Contains the two main components:
  - `MovieList`: Displays and manages the list of movies.
  - `SongsList`: Displays and manages the list of songs.
- **store**: Contains the Redux setup and slices:
  - `index.js`: Configures the Redux store.
  - `slices/`: Contains the Redux slices:
    - `movieSlice.js`: Manages the state and actions related to the movie list.
    - `songsSlice.js`: Manages the state and actions related to the songs list.
  - `actions`:Create Action for handling reset both list at once

## Installation and Setup

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/HeshamCaesar001/media-play-list.git
    cd mediaplaylist
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

4. Open your browser and navigate to `http://localhost:3000` to view the app.

## Usage

- **Adding Items**: Use the provided buttons to add a movie or a song to their respective lists.
- **Removing Items**: Click the remove button next to each item to delete it from the list.
- **Resetting Lists**: Click the reset button to clear both the movie and song lists.

## Technologies Used

- **React.js**: A JavaScript library for building user interfaces.
- **Redux**: A predictable state container for JavaScript apps.
- **Redux Toolkit**: The official, recommended way to write Redux logic.
- **JavaScript ES6**: Modern JavaScript syntax and features.
- **CSS**: For basic styling of the components.

