
Built by https://www.blackbox.ai

---

```markdown
# Bluetooth Lamp Controller

## Project Overview
The Bluetooth Lamp Controller is a web-based application designed to connect and control Bluetooth-enabled smart lamps. The application allows users to discover devices, adjust brightness levels, change colors, and manage device settings through an easy-to-use interface.

## Installation
To run the Bluetooth Lamp Controller on your local machine, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/bluetooth-lamp-controller.git
   cd bluetooth-lamp-controller
   ```

2. **Open `index.html` in your browser**
   Open the `index.html` file in a modern web browser (e.g., Chrome, Firefox) that supports the Web Bluetooth API.

3. **Run a local server (optional but recommended)**
   If using features that require CORS, consider running a local server. You can use simple servers like:
   - Python
     ```bash
     python -m http.server
     ```
   - Node.js (with `http-server`)
     ```bash
     npx http-server
     ```

## Usage
1. **Connect to a Device**
   - Click on the "Connect Device" button on the home page to initiate a Bluetooth scan.
   - Choose from the available devices presented in the interface.

2. **Control your Lamps**
   - After connecting, navigate to the **Control Panel** to adjust brightness, change colors, and toggle each lamp on or off.
   
3. **Adjust Settings**
   - Access the **Settings** page to manage your device connection preferences and handle device information.

## Features
- Bluetooth device discovery and connection.
- Control multiple smart lamps by adjusting brightness and color.
- User-friendly interface built with Tailwind CSS and Font Awesome icons.
- Device settings management including auto-connect options.

## Dependencies
This project requires the following libraries:
- [Tailwind CSS](https://tailwindcss.com/) - Version 3.0 or later, for styling.
- [Font Awesome](https://fontawesome.com/) - For icons used in the application.

## Project Structure
The project has the following structure:
```
/bluetooth-lamp-controller
│
├── index.html        # Home page for device connection
├── control.html      # Control panel for managing the smart lamps
├── settings.html     # Settings page for configuring device options
├── styles.css        # Custom styles complementing Tailwind CSS
└── README.md         # Project documentation
```

Each HTML file serves a specific purpose within the application, providing a straightforward flow for users to connect and manage their Bluetooth lamps.

---

For more details, feel free to reach out or contribute to the project!
```