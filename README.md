🚀 Daily JavaScript App - 19:
This repository is part of my Daily JavaScript Coding Challenge to build one JavaScript project every day. 🌟 The goal is to refine my JavaScript skills 🧠 while fostering consistency in coding. 💻✨



# Coming Soon Page

This project is a simple **"Coming Soon"** landing page with a countdown timer. It provides an interactive user interface displaying the time remaining until a specific launch date. Built with HTML, CSS, and JavaScript, it includes a countdown mechanism that updates every second.

---

## Features

- **Dynamic Countdown Timer**: Automatically calculates and displays the remaining days, hours, minutes, and seconds until the specified launch date.
- **Responsive Design**: Fully responsive and mobile-friendly layout.
- **Customizable**: Easily change the launch date, styles, and content to suit your needs.



## How It Works

1. **Countdown Logic (JavaScript)**:
   - The `countDownDate` is set in `app.js` using `new Date("Feb 9, 2025 00:00:00").getTime()`.
   - A `setInterval` function calculates the time difference between the current time and the target date every second.
   - The remaining time is broken into days, hours, minutes, and seconds, then dynamically updated in the HTML.

2. **HTML Structure**:
   - The timer values (`days`, `hours`, `minutes`, and `seconds`) are updated in `<p>` elements with corresponding `id` attributes.

3. **Fallback**:
   - If the countdown ends (`distance < 0`), the timer stops, and all values reset to "00".

---

## Customization

1. **Change the Launch Date**:
   - Update the `countDownDate` value in `app.js`:
     ```javascript
     var countDownDate = new Date("Your Date Here").getTime();
     ```

2. **Style the Page**:
   - Modify `style.css` to change colors, fonts, layout, or add animations.

3. **Replace Images**:
   - Add your own `logo.png` and `rocket.png` in the `img/` directory.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/enesatacan/ComingSoonPage
   ```
2. Open `index.html` in a browser to see the countdown page.

---

## Technologies Used

- **HTML5**: Structure of the page.
- **CSS3**: Styling and layout.
- **JavaScript**: Countdown logic and dynamic updates.

---

## Screenshots

![image](https://github.com/user-attachments/assets/8e2c1b7c-65dd-4680-ae9d-e87bb273de44)
