# NxtWatch App

NxtWatch is a video streaming application built using React that provides users with various video content, including trending, gaming, and saved videos. The app includes authentication, API requests, state management, and UI interactions.

## Features

### Login Route
- Displays an error message when invalid credentials are provided.
- Navigates to the Home route upon successful authentication.
- Redirects unauthenticated users to the Login route when accessing protected routes.
- Redirects authenticated users attempting to access the Login route to the Home route.
- Supports a "Show Password" checkbox to toggle password visibility.

### Home Route
- Fetches videos from the API and displays them.
- Shows a loader while fetching data.
- Displays a failure view if the API request fails.
- Implements search functionality for videos.
- Allows users to navigate to video details, trending, gaming, and saved videos.

### Trending Route
- Fetches and displays trending videos.
- Shows a loader while fetching data.
- Displays a failure view if the API request fails.
- Provides navigation to other sections of the app.

### Gaming Route
- Fetches and displays gaming-related videos.
- Shows a loader while fetching data.
- Displays a failure view if the API request fails.
- Provides navigation to other sections of the app.

### Video Item Details Route
- Fetches and displays details of a specific video.
- Shows a loader while fetching data.
- Displays a failure view if the API request fails.
- Integrates with `react-player` for video playback.
- Implements Like, Dislike, and Save buttons with state management.

### Saved Videos Route
- Displays a list of saved videos.
- Shows "No Saved Videos" view when the list is empty.
- Provides navigation to other sections of the app.

### Not Found Route
- Displays a "Not Found" page for invalid routes.

### Theme Toggle
- Allows users to switch between dark and light themes.

### Logout Functionality
- Displays a logout confirmation popup.
- Cancels logout if the user selects "Cancel".
- Logs out the user and redirects to the Login route upon confirmation.

## Technologies Used
- React.js
- React Router
- React Player
- Authentication using JWT
- API Integration
- CSS for styling

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/UmaMaheshkondaveti/nxtWatchApp.git
   ```
2. Navigate to the project directory:
   ```sh
   cd nxtWatchApp
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm start
   ```
   
