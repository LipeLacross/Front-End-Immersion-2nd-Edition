## 🌐 [Versão em Português do README](README.md)

# Spotify Imersão
# Front-End-Immersion-2nd-Edition

This is a React project designed to simulate an interface similar to Spotify, using reusable components to create an interactive navigation experience. The app consists of a sidebar, a header with controls and search, a main area for playlists, and an artists section.

## 🔨 Project Features

- **Sidebar (Navigation):** Displays the Spotify logo, navigation links to "Home", "Search", and the user's library, and also allows playlist creation.
- **Header:** Contains navigation buttons (arrows), a search bar, and options for login and registration.
- **Main Area:** Displays a list of playlists and a section for displaying artists.
- **Footer:** Offers a chance to try Premium for free with a signup button.

### Visual Example of the Project
![chrome-capture-2025-4-1](https://github.com/user-attachments/assets/f89b91a3-1077-406a-8989-c205f6333ad3)

## ✔️ Techniques and Technologies Used

- **React:** Library for building the interface.
- **JavaScript (ES6+):** Language for manipulating the application's logic.
- **HTML5 & CSS3:** Structure and styling of the application.
- **FontAwesome:** Icon library used to enhance the interface.
- **Create React App:** Tool for initializing the project with basic configurations.

## 📁 Project Structure

- **public/**
  - `favicon.ico`: Site icon.
  - `index.html`: Main HTML file for the app.
  - `manifest.json`: App settings for PWA.
  - `robots.txt`: Instructions for search engines.

- **src/**
  - **App.js**: Main component that organizes other components.
  - **App.test.js**: Unit tests for the `App` component.
  - **api-artists/**
    - `artists.json`: Artist data used in the application.
  - **assets/**
    - **icons/**: Contains icons such as the Spotify logo and navigation icons.
    - **playlist/**: Images of playlists for display.
  - **components/**
    - **Footer/**: Component rendering the footer.
      - `Footer.js`: Footer component with Premium offer call-to-action.
    - **Header/**: Header component with search and buttons.
      - `Header.js`: Header implementation with navigation arrows and search bar.
    - **Main/**: Main component displaying playlists.
      - `Main.js`: Renders playlists and artist results.
    - **Sidebar/**: Sidebar navigation component.
      - `Sidebar.js`: Displays the navigation menu and language settings.
  - `index.js`: Entry point for React.
  - `reportWebVitals.js`: Performance monitoring for the app.
  - `setupTests.js`: Configuration for Jest tests.

## 🛠️ Run the Project Locally

To run the project locally, follow the steps below:

1. **Make sure Node.js is installed:**
   - [Node.js](https://nodejs.org/) is required to run the project. You can check if it's installed by running:

   ```bash
   node -v
   ```

- If not installed, download and install the recommended version.

2. **Clone the Repository:**
    - Copy the repository URL and run the following command in the terminal:

   ```bash
   git clone <REPOSITORY_URL>
   cd project-directory
   ```

3. **Install Dependencies:**

   ```bash
   npm install
   ```

4. **Start the application:**

   ```bash
   npm start
   ```

   The app will start in your browser, typically at `http://localhost:3000`.

## 🌐 Deploy

To deploy the application, you can use services like:

- **[Vercel](https://vercel.com/)**
- **[Netlify](https://www.netlify.com/)**
- **[GitHub Pages](https://pages.github.com/)**
