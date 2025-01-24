
# Kitchen

A fictional culinary website showcasing CSS animations and design.

## Project Structure

The project consists of the following files and directories:

- `index.html`: The main HTML file that structures the web page.
- `styles.scss`: The main SCSS file containing styles for the website.
- `styles.css`: The compiled CSS file generated from `styles.scss`.
- `styles.css.map`: The source map file for `styles.css`.
- `main.js`: The JavaScript file containing interactive functionalities.
- `icon.png`: An icon image used in the website.
- `img/`: Directory containing additional images used in the website.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `.firebaserc`: Firebase project configuration file.
- `firebase.json`: Firebase hosting configuration file.

## Technologies Used

- **HTML**: Structures the content of the web page.
- **SCSS**: A CSS preprocessor used for writing maintainable and scalable styles.
- **JavaScript**: Adds interactivity to the web page.
- **Firebase Hosting**: Hosts the web application.

## Setup and Installation

To set up and run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/cenanionut/kitchen.git
   cd kitchen
   ```

2. **Install dependencies**:
   Ensure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed. Then, install the necessary npm packages:
   ```bash
   npm install
   ```

3. **Compile SCSS to CSS**:
   If you're using a build tool or task runner (e.g., Gulp, Webpack), run the appropriate command to compile `styles.scss` to `styles.css`. If not, you can use the `sass` command-line tool:
   ```bash
   sass styles.scss styles.css
   ```

4. **Run the application**:
   Open `index.html` in your preferred web browser to view the website locally.

## Firebase Deployment

To deploy the application using Firebase Hosting:

1. **Install Firebase CLI**:
   ```bash
   npm install -g firebase-tools
   ```

2. **Login to Firebase**:
   ```bash
   firebase login
   ```

3. **Initialize Firebase in the project directory**:
   ```bash
   firebase init
   ```
   Select the appropriate Firebase project and hosting setup during the initialization.

4. **Deploy to Firebase Hosting**:
   ```bash
   firebase deploy
   ```

## Contributing

If you wish to contribute to this project:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature-branch
   ```
3. **Make your changes**.
4. **Commit your changes**:
   ```bash
   git commit -m "Description of changes"
   ```
5. **Push to your fork**:
   ```bash
   git push origin feature-branch
   ```
6. **Create a pull request**.

## License

This project is licensed under the [MIT License](LICENSE).
