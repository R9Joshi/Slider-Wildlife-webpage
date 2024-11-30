# Slider-Wildlife-webpage
A fully functional carousel with animated transitions, thumbnails, and auto-slide features built using HTML, CSS, and JavaScript. The carousel includes options for navigating through items via 'next' and 'prev' buttons, as well as automatic transitions every 7 seconds.
# Carousel with Animated Transitions

## Overview
This is a responsive carousel built using **HTML**, **CSS**, and **JavaScript**. The carousel features smooth transition effects, automatic sliding, and dynamic thumbnail navigation. It allows users to cycle through items manually using the 'next' and 'prev' buttons or let the carousel run automatically after a set interval.

## Features
- **Next/Previous Navigation**: Use the buttons to navigate through carousel items.
- **Auto-slide**: Items will automatically transition every 7 seconds.
- **Thumbnails**: Thumbnail images are displayed at the bottom of the carousel, which dynamically update with the carousel items.
- **Animations**: Smooth sliding and fading effects for items and thumbnails.
- **Responsive Design**: Adjusts layout on smaller screens (optimized for mobile view).

## Tech Stack
- **HTML**: Structure and layout of the carousel.
- **CSS**: Styling the carousel, implementing transitions, and animations.
- **JavaScript**: Handling the functionality for navigation, auto-sliding, and the dynamic behavior of carousel items.

## Getting Started

To get a local copy of the project up and running:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/carousel-animated.git
    ```
2. **Open the index.html file** in your browser to view the carousel in action.

## How It Works

- **HTML**: Provides the structure for the carousel and navigation controls.
- **CSS**: Defines the styles, including animations for transitioning between carousel items and thumbnails.
- **JavaScript**: Controls the logic for navigating between slides (manually or automatically), updates the thumbnail position, and resets the auto-slide timer.

### Key Functions:
1. **Next and Previous Navigation**:
   - Clicking the **next** button moves the carousel to the next item and cycles the thumbnails.
   - Clicking the **prev** button moves the carousel to the previous item and cycles the thumbnails in reverse.

2. **Auto-slide**:
   - The carousel automatically slides to the next item every 7 seconds (`timeAutoNext`).

3. **Animation**:
   - Items slide in and out smoothly with CSS animations, and thumbnail images animate during transitions.

## Customization

You can customize the following properties:
- `timeAutoNext`: Controls the auto-slide interval (currently set to 7 seconds).
- `timeRunning`: Controls the duration of the animation during each slide transition (currently set to 3 seconds).
- **CSS Styles**: Modify the appearance, such as fonts, colors, and layout to fit your design needs.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### **Screenshots**:
Add any relevant screenshots here if applicable (e.g., carousel in action).

## Acknowledgments
- This project was inspired by modern web design practices and carousel functionalities.

---

