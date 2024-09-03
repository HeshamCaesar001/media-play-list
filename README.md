# 🎬🎵 MediaPlaylist

**MediaPlaylist** is a React application that showcases my skills in integrating **Redux** and **Redux Toolkit** for state management. The app allows users to manage two separate lists—one for movies 🎬 and another for songs 🎵. Users can easily add items to these lists, remove individual items, or reset both lists entirely with a single click.

## 🚀 Project Overview

This project serves as a demonstration of using **Redux** and **Redux Toolkit** in a modern **React.js** application. It includes two main components: `MovieList` and `SongsList`, each responsible for displaying and managing their respective media lists. The project structure emphasizes modularity and best practices in state management with Redux slices.

## ✨ Features

- **Add Movies and Songs**: Users can add their favorite movies 🎥 or songs 🎶 to the respective lists.
- **Remove Items**: Each list item comes with a remove button ❌, allowing users to delete individual movies or songs.
- **Reset Lists**: A reset button 🔄 is available to clear both the movies and songs lists at once.
- **State Management**: The application utilizes Redux for managing the state of the lists, with dedicated slices for movies and songs.

## 📂 Project Structure

The project is organized into the following directories within the `src` folder:

- **components**: Contains the two main components:
  - `MovieList`: Displays and manages the list of movies 🎬.
  - `SongsList`: Displays and manages the list of songs 🎵.
- **store**: Contains the Redux setup and slices:
  - `index.js`: Configures the Redux store.
  - `slices/`: Contains the Redux slices:
    - `movieSlice.js`: Manages the state and actions related to the movie list 🎥.
    - `songsSlice.js`: Manages the state and actions related to the songs list 🎶.
  - `actions`:Create Action for handling reset both list at once .


## 🛠️ Installation and Setup

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/HeshamCaesar001/media-play-list.git
    cd mediaplaylist
    ```

2. **Install the dependencies**:
    ```bash
    npm install
    ```

3. **Start the development server**:
    ```bash
    npm start
    ```

4. **Open your browser** and navigate to `http://localhost:3000` to view the app.

## 🎮 Usage

- **Adding Items**: Use the provided buttons ➕ to add a movie or a song to their respective lists.
- **Removing Items**: Click the remove button ❌ next to each item to delete it from the list.
- **Resetting Lists**: Click the reset button 🔄 to clear both the movie and song lists.

## 🛠️ Technologies Used

- **React.js**: A powerful JavaScript library for building user interfaces.
- **Redux**: A predictable state container for JavaScript apps.
- **Redux Toolkit**: The official, recommended way to write Redux logic with a modern API.
- **JavaScript ES6**: Utilizing modern JavaScript syntax and features.
- **CSS**: For styling the components with a clean and responsive layout.


---

Built with ❤️ by [Hisham Sayed](https://github.com/HeshamCaesar001).






