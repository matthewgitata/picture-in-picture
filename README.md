# Picture-in-Picture Project

## Overview

The Picture-in-Picture (PiP) project creates a virtual second screen that can be moved and resized, allowing it to stay on top of all other windows. This functionality enhances user experience by enabling simultaneous viewing of media while interacting with other applications.

## Live Demo

You can try the live version of the Quote Generator here:  
[Live Demo](https://matthewgitata.github.io/picture-in-picture/)

## Features

- Resizable and Movable Window: Users can adjust the size and position of the PiP window as needed.
- Media Stream Selection: Prompts users to select a media stream, which is then passed to a video element for playback.
- Screen Capture API Integration: Utilizes the Screen Capture API to capture live stream contents, providing a seamless streaming experience.
- One-Click Activation: Users can trigger the PiP functionality simply by pressing the start button.

## Technologies Used

- Font: Google Font - Allerta
- APIs:
  - [Screen Capture API](https://developer.mozilla.org/en-US/docs/Web/API/Screen_Capture_API/Using_Screen_Capture)
  - [Picture-in-Picture API](https://css-tricks.com/an-introduction-to-the-picture-in-picture-web-api/)

## Installation

To get started with the Picture-in-Picture project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/matthewgitata/picture-in-picture.git
   ```
2. Navigate to the project directory:
   ```bash
   cd picture-in-picture
   ```
3. Open index.html in your preferred web browser.

## Usage

1. Click the Start button to initiate the screen sharing process.
2. Select the desired screen or video to share.
3. The PiP window will appear, allowing you to resize and move it as needed.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m "Add some feature"
   ```

4. Push to the branch:

   ```bash
   git push origin feature/YourFeatureName
   ```

5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE file](./LICENSE.txt) for details.

## Acknowledgments

- Special thanks to the developers of the Screen Capture API and Picture-in-Picture API for providing robust tools that enhance web applications.
