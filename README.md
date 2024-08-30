# GitHub Profile Viewer

This project is a simple web application that allows users to view GitHub profiles by entering a username. The application fetches the user's profile details and repositories from the GitHub API and dynamically displays them on the page.

## Features

- **User Profile Retrieval**: Displays GitHub user profile information such as avatar, name, email (if available), and location.
- **Repository List**: Fetches and displays the user's public repositories, including options to view the repository on GitHub or a live demo (if available).
- **Interactive Design**: Includes hover effects, animations, and responsive styling using Bootstrap and custom CSS for a better user experience.
- **Error Handling**: Provides feedback and alerts the user if the GitHub username is invalid, does not exist, or there is an error in fetching data from the GitHub API.
- **Loading Spinner**: Shows a loading indicator while data is being fetched from the GitHub API to ensure a smooth user experience.
- **Responsive Layout**: The design adjusts gracefully across various devices, ensuring a seamless experience whether on mobile, tablet, or desktop.

## Built With

- **HTML5**
- **CSS3** (Custom styles and Bootstrap)
- **JavaScript**: Handles the core functionality of API calls and dynamic content rendering.
- **Bootstrap 5**: Utilized for responsive layout and styling, making the application mobile-friendly.
- **FontAwesome**: Provides scalable vector icons for a visually appealing UI.
- **SweetAlert2**: For customizable and stylish alert messages when errors occur or when a GitHub profile is not found.
- **GitHub API**: The RESTful API that enables fetching user profile data and repositories.


### Prerequisites

- A modern web browser with JavaScript enabled (e.g., Chrome, Firefox, Edge, etc.).
- Internet access to connect to the GitHub API.

### Usage

1. Enter a valid GitHub username in the input field.
2. Click on the **Get Profile** button.
3. The user's profile details, including their avatar, name, email (if available), location, and repositories, will be dynamically shown on the page.

## Example

To view a GitHub user profile, enter a username such as `Shozon-Roy` and click the **Get Profile** button. The profile picture, name, location, and repositories will be displayed dynamically. You can also click on each repository to visit its page on GitHub or view a live demo (if available).


### Live Demo

Project Live Link [here](https://shozon-roy.github.io/Github-Profile-Viewer/). 
