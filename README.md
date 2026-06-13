# Analog Clock Project

## Overview

A modern analog clock built using HTML, CSS, and JavaScript. The clock features a clean dark-themed design, glowing accents, styled clock hands, and a responsive circular clock face that displays the current time in real-time.

## Features

* Real-time analog clock
* Hour, minute, and second hands
* Responsive circular clock face
* Modern dark theme
* Glowing visual effects
* Center pivot point
* Clean and customizable CSS styling
* Lightweight and beginner-friendly codebase

## Technologies Used

* HTML5
* CSS3
* JavaScript

## Project Structure

```text
Analog-Clock/
│
├── index.html
├── analogstyle.css
├── script.js
└── README.md
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/analog-clock.git
```

### 2. Navigate to the Project Folder

```bash
cd analog-clock
```

### 3. Open the Project

Open `index.html` in your browser or use a live server extension in your code editor.

## How It Works

The clock uses JavaScript to retrieve the current system time and calculate the rotation angles for:

* Hour hand
* Minute hand
* Second hand

The hands are rotated using CSS transforms to accurately represent the current time.

## Customization

### Change Background Color

Edit the `body` selector in `analogstyle.css`:

```css
body {
    background: #0f172a;
}
```

### Change Clock Size

Modify the clock dimensions:

```css
.clock {
    width: 320px;
    height: 320px;
}
```

### Change Hand Colors

Update the CSS variable values:

```html
<i style="--clr:#38bdf8"></i>
```

## Future Improvements

* Digital clock display
* Multiple time zones
* Theme switcher
* Smooth second-hand movement
* Glassmorphism effects
* Alarm functionality
* Date and day display

## Screenshots

Add screenshots of your project here.

## Learning Outcomes

This project demonstrates:

* CSS positioning
* CSS transforms and rotations
* Flexbox layout
* CSS variables
* DOM manipulation
* JavaScript date and time functions
* Responsive UI design

## License

This project is open source and available under the MIT License.

## Author

Created as a front-end development project to practice HTML, CSS, JavaScript, positioning, transforms, and responsive design.
