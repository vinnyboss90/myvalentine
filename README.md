# Valentine's Day Proposal Animation

A fun and interactive Valentine's Day proposal animation featuring a bouncing heart and interactive buttons. The project is built using HTML, CSS, and JavaScript.

![Preview](preview.gif) <!-- Add a preview GIF if available -->

## Features
- **Bouncing Heart Animation**: A heart that bounces up and down using CSS keyframes.
- **Interactive Buttons**:
  - **Yes Button**: Cycles through messages before exploding the heart with a joyful animation.
  - **No Button**: Cycles through messages, eventually thanking the user for not breaking the heart.
- **Modern Design**: Stylish gradient background, smooth transitions, and responsive design.

## How It Works
1. The heart bounces continuously using a CSS animation.
2. When the user clicks "Yes":
   - First click: Asks, "Are you sure? 😊"
   - Second click: Asks, "Really sure? 🥰"
   - Third click: Displays, "Yay! You made my heart boom with joy! 💥" and the heart explodes.
3. When the user clicks "No":
   - First click: Asks, "Are you sure? 😢"
   - Second click: Displays, "My heart will break... 💔"
   - Third click: Displays, "Thank you for not breaking my heart. ❤️" and hides the "No" button.

## How to Use
1. Clone or download the repository.
2. Open the `index.html` file in your browser.
3. Interact with the "Yes" and "No" buttons to see the animations and messages.

## Code Structure
- **HTML**: The structure of the page, including the heart, message, and buttons.
- **CSS**: Styles for the heart animation, buttons, and overall layout.
- **JavaScript**: Logic for handling button clicks and updating the messages.

## Customization
- **Change Messages**: Modify the text in the `handleYes()` and `handleNo()` functions in the JavaScript file.
- **Change Colors**: Update the gradient background in the `body` CSS or button colors in the `.btn-yes` and `.btn-no` classes.
- **Add Animations**: Add or modify CSS keyframes for additional animations.

## Technologies Used
- HTML
- CSS (with keyframe animations)
- JavaScript

## License
This project is open-source and available under the [MIT License](LICENSE). Feel free to use, modify, and share it!
