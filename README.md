# Swiggy Homepage Clone

This project is a static clone of the Swiggy homepage, a food delivery platform, built using HTML and CSS. The website features a responsive layout with a navigation bar, hero section, feature cards, app promotion section, and a footer, designed to mimic Swiggy's branding and user interface.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Responsive Design](#responsive-design)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Navigation Bar**: Includes a logo, Login, and Sign Up buttons, with the Sign Up button featuring a hover effect that changes its style.
- **Hero Section**: A split layout with text on the left (tagline, location input, and popular cities) and a large banner image on the right.
- **Feature Cards**: Three cards highlighting Swiggy's key features (No Minimum Order, Live Order Tracking, Lightning-Fast Delivery) with images, titles, and descriptions.
- **App Promotion Section**: Promotes the Swiggy mobile app with text, app store badges, and a phone image showcasing the app.
- **Footer**: Four columns with company info, contact details, legal links, and app store badges for downloading the Swiggy app.
- **Interactive Elements**: Hover effects on the Sign Up button and consistent styling for buttons and inputs.

## Technologies Used
- **HTML5**: For the structure of the webpage.
- **CSS3**: For styling, including flexbox for layout, hover effects, and custom fonts (Poppins and Arial).
- **External Resources**:
  - Poppins font (loaded via CSS, assumed to be available through a browser or CDN).
  - External images for the logo (`logo1.png`), hero banner (`banner1.webp`), feature cards (`nominimumorder.webp`, `liveordertracking.webp`, `fastdeliver.webp`), app promotion (`pixel_wbdy4n`), and app store badges (`iOS_ajgrty`, `play_ip0jfp`).

## File Structure
```
├── swiggy.html       # Main HTML file
├── index.css         # Custom CSS for styling
├── images/           # Folder containing images
│   ├── logo1.png
│   ├── banner1.webp
│   ├── nominimumorder.webp
│   ├── liveordertracking.webp
│   ├── fastdeliver.webp
│   ├── pixel_wbdy4n
│   ├── iOS_ajgrty
│   ├── play_ip0jfp
└── README.md         # Project documentation
```

## Setup Instructions
1. **Clone or Download the Repository**:
   ```bash
   git clone <repository-url>
   ```
   Alternatively, download the project files as a ZIP and extract them.

2. **Ensure Image Assets**:
   - Place all required images (`logo1.png`, `banner1.webp`, `nominimumorder.webp`, `liveordertracking.webp`, `fastdeliver.webp`, `pixel_wbdy4n`, `iOS_ajgrty`, `play_ip0jfp`) in the `images/` folder.
   - Update image paths in `index.html` if necessary.

3. **Open the Project**:
   - Navigate to the project folder.
   - Open `index.html` in a web browser to view the webpage.

4. **Dependencies**:
   - No external CDNs or dependencies are required, as the project relies solely on HTML and CSS.
   - Ensure the Poppins font is available (it may load via browser defaults or require a Google Fonts import if not available locally).

## Usage
- **Navigation**: Click the Login or Sign Up buttons (placeholders) in the navbar. Hover over the Sign Up button to see the style change.
- **Hero Section**: Enter a delivery location in the input field (static placeholder) or view popular cities listed below.
- **Feature Cards**: Read about Swiggy's key features (No Minimum Order, Live Order Tracking, Lightning-Fast Delivery).
- **App Promotion**: View the Swiggy app promotion with app store badges (placeholders for App Store and Google Play links).
- **Footer**: Explore company, contact, and legal links (placeholders) or view app store badges.

## Responsive Design
The current design uses flexbox for layout but lacks media queries, so it is not fully responsive. Key considerations:
- **Desktop**: The layout displays a two-column hero section, three feature cards in a row, and a four-column footer.
- **Smaller Screens**: The design may not adapt well to mobile or tablet devices due to fixed widths (e.g., 400px input field, 540px hero image height). Flexbox provides some flexibility, but elements may overflow or misalign on smaller screens.
- **Recommendation**: Add media queries to adjust font sizes, image widths, and layout (e.g., stack elements vertically) for mobile and tablet devices.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Suggestions for improvement include adding media queries for responsiveness, implementing JavaScript for interactive features (e.g., form validation), or enhancing accessibility with ARIA attributes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Inspired by the Swiggy website, created as a static clone for educational purposes.*
