# KECUENZA IT Portfolio Website

## Overview
This portfolio showcases Kent Edmark D. Cuenza's IT skills and projects. It includes sections like **About Me**, **Specialization**, **Projects**, and **Experience**. The website is responsive and user-friendly, built with modern web technologies.

## Design Choices

### 1. **Typography & Colors**
   - **Fonts**: Georgia for headers, Avenir for subheaders and text, providing a balance of professionalism and modernity.
   - **Colors**: A greenish-blue (`#3bba9c`) as the highlight color against dark backgrounds (`#2e3047` and `#3c3f58`), creating a sleek, tech-inspired look.

### 2. **Layout & Responsiveness**
   - **Fixed Header**: Navigation remains accessible during scrolling.
   - **Responsive Design**: Media queries ensure the layout adapts across devices, optimizing user experience on both desktop and mobile.

### 3. **Interactivity**
   - **Image Hover Effects**: Smooth transitions to engage users visually.
   - **Sliders**: Used for showcasing skills and projects efficiently without cluttering the page.

## Challenges & Solutions

### 1. **Image Slider Responsiveness**
   - **Challenge**: Images were cut off on smaller screens.
   - **Solution**: Used `scroll-snap` and `flexbox` to ensure smooth scrolling and alignment on all devices.

### 2. **Fixed Header Overlap**
   - **Challenge**: Fixed header overlapped sections.
   - **Solution**: Implemented `scroll-padding-top` to ensure proper alignment when navigating.

### 3. **Hover Effect Inconsistencies**
   - **Challenge**: Hover effects were jittery on different browsers.
   - **Solution**: Fine-tuned CSS transitions for smooth, cross-browser compatibility.

## How to Use
1. Clone or download the repository:
   ```bash
   git clone https://github.com/KenZa0705/portfolio.git
   ```
2. Open `index.html` in a browser.

## Tech Stack
- **HTML5**: Structure and content.
- **CSS3**: Styling and responsiveness.
- **Bootstrap 5.3**: Mobile-first design.

## License
This project is licensed under the MIT License.
