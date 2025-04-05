# Magical Landing Page

A responsive landing page template with a magical/fantasy theme, built with HTML and Tailwind CSS.

## Features

- Responsive design for all device sizes
- Fantasy-themed styling with elegant fonts
- Pre-configured Tailwind CSS with custom colors and fonts
- Ready-to-use Google Fonts integration:
    - Cinzel (for headings)
    - PT Serif (for body text)
    - Sigmar (display font)
- Font Awesome icons included via CDN
- Custom color palette:
    - dark-blue: #0a0a20
    - navy-blue: #0d1933
- Hero section background image setup

## Installation

No installation required - just copy the HTML file and start building your content within the `<body>` tags.

## Usage

1. Add your content within the `<body>` section
2. Use the pre-configured Tailwind classes:
    - Font families: `font-cinzel` or `font-pt-serif`
    - Colors: `bg-dark-blue`, `text-navy-blue`, etc.
3. Customize the Tailwind config in the `<script>` tag if needed

## Dependencies

- [Tailwind CSS](https://tailwindcss.com) (included via CDN)
- [Font Awesome](https://fontawesome.com) (included via CDN)
- Google Fonts (included via CDN)

## Customization

To customize the theme:

1. Modify the `tailwind.config` object in the `<head>` section
2. Add or change colors in the `colors` object
3. Add additional font families as needed
4. Update the background image by changing the `hero-pattern` URL

## Notes

- The favicon line is currently commented out - uncomment and point to your favicon image
- Background image path is set to "images/background.png" - create this directory and add your image

## License

Free to use for personal and commercial projects. Attribution is appreciated but not required.