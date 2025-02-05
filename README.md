City Skyline - CSS Art Project
City Skyline Preview Replace with actual screenshot

A responsive city skyline illustration created purely with HTML and CSS. This project demonstrates advanced CSS techniques including gradient backgrounds, CSS variables, flexbox layouts, and media queries.

Features
🏙️ Pure CSS artwork with no images

🎨 Dynamic color schemes using CSS variables

📱 Responsive design with mobile adaptation

🌆 Layered foreground/background buildings

🪟 Detailed window patterns using CSS gradients

🌇 Animated sky gradient background

Technologies Used
HTML5

CSS3:

CSS Variables

Flexbox

Linear Gradients

Radial Gradients

Media Queries

Positioning

Installation
Clone the repository:

bash
Copy
git clone https://github.com/your-username/city-skyline-css.git
Open index.html in your web browser

No dependencies required - works in any modern web browser!

Usage
Simply open the index.html file to view the city skyline. The artwork will automatically adapt to your screen size:

Desktop: Colorful building scheme with gradient sky

Mobile (< 1000px): Dark mode adaptation with night sky

Try resizing your browser window to see the color scheme change!

Project Structure
Copy
city-skyline/
├── index.html
├── css/
│   └── styles.css
└── README.md
Key Components:
Sky Background
Created using a radial gradient that simulates sunlight

Building Layers

Background buildings (background-buildings div)

Foreground buildings (foreground-buildings div)

Building components created with nested divs and CSS shapes

CSS Techniques

Flexbox for building layout

CSS Variables for color management

Gradient borders for triangular shapes

Repeated gradients for window patterns

Customization
Modify the colors by changing these CSS variables in styles.css:

css
Copy
:root {
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
  --building-color4: #538cc6;
  --window-color1: #bb99ff;
  --window-color2: #8cd9b3;
  --window-color3: #d98cb3;
  --window-color4: #8cb3d9;
}
Contributing
Contributions are welcome! Here are some ways to improve the project:

Add more building variations

Implement animation effects

Enhance mobile responsiveness

Add interactive elements with JavaScript

Create seasonal color themes

Please follow standard GitHub pull request process.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Inspired by CSS art tutorials and examples

Color palettes from Coolors.co

CSS gradient techniques from MDN Web Docs
