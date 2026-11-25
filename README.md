# Web Development Workshop Registration Page

A responsive workshop registration form built with HTML and CSS (Task 11.2). The layout adapts to desktop, tablet and mobile screens.


## Features
- Registration form with Username, Email, Phone No, Number of seats and Second Username fields
- Icons and red `*` marks for required fields
- Submit and Cancel buttons
- Fully responsive: the image is on the left and the form on the right on large screens, and they stack vertically on small screens
- Buttons become full width on mobile

## Technologies Used
- HTML5
- CSS3 (Flexbox, `flex-wrap`, `clamp()`, media query)
- Google Font: Nunito
- Deployed on Netlify

## Responsive Approach
- `flex: 1 1 250px` and `flex: 1 1 300px` let the image and form wrap automatically on narrow screens
- `min-height` and `min-width: 0` prevent overflow
- One media query (`max-width: 480px`) adjusts padding and makes buttons full width

## Project Structure
```
Task11.2-CSS/
├── index.html
├── stye.css
├── workshop.webp
└── README.md
```

## How to Run
1. Clone the repository: `git clone https://github.com/shanmugashobana/Task11.2-CSS.git`
2. Open `index.html` in any browser
3. Resize the window or use Chrome DevTools (`Ctrl+Shift+M`) to test different devices

## Tested Screen Sizes
- Desktop (1280px)
- Tablet (768px)
- Mobile (375px, 320px)

## Author
Shanmuga Shobana
GitHub: [shanmugashobana](https://github.com/shanmugashobana)
