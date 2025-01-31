# OpenPWA

OpenPWA is a project designed to create small web apps for iOS and Android by leveraging iOS configuration profiles and a dedicated Android app. This project is currently in development, allowing the creation of both stateless and stateful web apps, depending on hosting availability.

[Visit the page and install the PWA from the side menu](https://tbrainrush.github.io/OpenPWA/)

## Features

- **Web App Creation**: Easily create web apps that can be installed on iOS and Android devices.
- **iOS Configuration Profiles**: Install web apps directly on iOS devices using configuration profiles.
- **Android App Integration**: Install web apps on Android via a dedicated app that adds home screen shortcuts with custom names and icons.
- **Full-Screen Experience**: On Android, web apps run in a WebView for an immersive, native-like experience.
- **Cross-Platform**: Designed for iOS and Android, but accessible from any device with a web browser.
- **Local Installation Link**: Share a link to install a PWA even if it is not hosted anywhere, by executing the code locally.

## How to Use

### On iOS
1. **Create Your Web App**:
   - Use the OpenPWA editor to write your HTML, CSS, and JavaScript code.
   - Customize the app title, description, and icon.

2. **Install the Web App**:
   - Generate the configuration profile and install it on your iOS device.
   - The web app will be added to your home screen and can be launched like any other app.

### On Android
1. **Install the OpenPWA Android App**:
   - To use OpenPWA on Android, you need to install the dedicated Android app.

2. **Create and Install the Web App**:
   - Use the OpenPWA editor to create your web app.
   - Open the OpenPWA Android app, add the web app as a home screen shortcut with a custom name and icon.
   - The web app will open in full-screen WebView mode for a native-like experience.

### Hosting (Optional)
- If you need a stateful web app, you can host it on GitHub Pages, Altervista, or any other hosting service.
- Stateless web apps can be created and installed without hosting, but they will not retain state between sessions.
- You can also share a link to install a PWA even if it is not hosted, allowing execution directly from local storage.

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

This project is currently in development. I'm working on adding more features and improving the user experience. If you encounter any issues or have suggestions, please open an issue on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

