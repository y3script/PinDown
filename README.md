# PinDown

**PinDown** is a Python GUI application for downloading images and videos from the Pinterest website. It utilizes `customtkinter` for the user interface and provides a simple and intuitive experience for users.

## Features

- **Simple GUI**: A user-friendly interface built with `customtkinter`.
- **Multi-threaded Downloads**: Efficient and fast downloads using multi-threading.
- **Custom Download Location**: Choose your preferred download directory.
- **Progress Indicator**: Real-time download progress indicator.
- **Dark Mode**: A visually appealing dark mode theme.

## Installation

To get started with PinDown, follow these steps:

1. **Clone the repository**:
   
   sh
   
   Copy code
   
   `git clone https://github.com/yourusername/pindown.git cd pindown`

2. **Install the required packages**:
   
   sh
   
   Copy code
   
   `pip install customtkinter pillow pypdl`

3. **Run the application**:
   
   sh
   
   Copy code
   
   `python pindown.py`

## Usage

1. Launch the application by running the `pindown.py` script.
2. Enter the Pinterest media link in the provided text entry field.
3. Click the "Download" button to start downloading.
4. The progress bar will show the download progress.
5. Once the download is complete, a message box will appear confirming the successful download.

## Code Overview

Here’s a brief overview of the main components in the code:

- **Main Application (`App` Class)**:
  - Initializes the GUI components and sets up the menu.
  - Handles user interactions and starts the download process.
- **Download Functionality (`download` method)**:
  - Manages the download process, including setting the download directory and updating the progress.
- **About Section (`about` method)**:
  - Displays an about dialog with information about the developer.

## Screenshots

![(Add screenshots of your application here if available.)](https://raw.githubusercontent.com/y3script/PinDown/main/Screenshots/PinDown_gui_01.png)
![(Add screenshots of your application here if available.)](https://raw.githubusercontent.com/y3script/PinDown/main/Screenshots/PinDown_gui_02.png)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the existing code style and add comments where necessary.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

Made by Y3script. For more info, contact me via [social media](https://bio.link/y3script).
