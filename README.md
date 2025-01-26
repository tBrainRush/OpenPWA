# OpenPWA

OpenPWA is a project designed to create small web apps for iOS by leveraging iOS configuration profiles. This project is currently in development, and while it is possible to create stateless web apps without hosting, the only way to have a stateful web app at the moment is to host it somewhere.

[Install OpenPWA as configuration profile](profile/OpenPWA.mobileconfig)

## Features

- **Web App Creation**: Easily create web apps that can be installed on iOS devices.
- **Configuration Profiles**: Utilize iOS configuration profiles to install web apps directly on devices.
- **Cross-Platform**: Although primarily designed for iOS, the web apps can be accessed from any device with a web browser.

## How to Use

1. **Create Your Web App**:
   - Use the editor provided in the OpenPWA interface to write your HTML, CSS, and JavaScript code.
   - Customize the app title, description, and icon.

2. **Install the Web App**:
   - Generate the configuration profile and install it on your iOS device.
   - The web app will be added to your home screen and can be launched like any other app.

3. **Host Your Web App (Optional)**:
   - If you need a stateful web app, you can host it on GitHub Pages, Netlify, or any other hosting service.
   - Stateless web apps can be created and installed without hosting, but they will not retain state between sessions.

## Contributing

We welcome contributions from the community! If you have created a web app using OpenPWA, you can share it with others by submitting a pull request to add your app to the list below. Here’s how:

1. **Create Your Repository**:
   - Create a new repository on GitHub for your web app.
   - Include the following files in your repository:
     - `index.html`: The main HTML file for your app.
     - `screenshot.png`: A screenshot of your app.
     - `README.md`: A brief description of your app and how to use it.

2. **Submit a Pull Request**:
   - Fork the OpenPWA repository.
   - Add a link to your app's repository in the `Community Apps` section of the README.md file.
   - Submit a pull request to the main OpenPWA repository.
   - Once approved, your app will be listed in the official repository.

## Community Apps

Work in progress...

## Development Status

This project is currently in development. We are working on adding more features and improving the user experience. If you encounter any issues or have suggestions, please open an issue on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
