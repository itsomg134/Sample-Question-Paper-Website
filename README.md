# Sample Question Paper Website

A clean, modern, and responsive static website for browsing and previewing sample question papers. Built with HTML, CSS, and vanilla JavaScript, this repository provides a ready-to-use template for educational platforms, coaching institutes, or personal project portfolios.

![Sample Question Paper Website Preview](https://via.placeholder.com/800x400?text=Question+Paper+Website+Preview)

## Features

- **Organized Paper Grid** – Browse question papers with clean cards showing subject, date, duration, and description
- **Filter & Search UI** – Interactive filter tabs and search bar (UI demo with visual feedback)
- **Featured Section** – Highlight important papers or exam sets
- **Question Preview** – See actual question formats and marking schemes
- **Fully Responsive** – Works seamlessly on desktop, tablet, and mobile devices
- **Modern Design** – Clean interface with soft gradients, cards, and thoughtful typography

## Live Demo

[View Live Demo](#) *(Add your deployment link here)*

## Technologies Used

- HTML5
- CSS3 (Flexbox & Grid, custom properties)
- Google Fonts (Inter)
- Vanilla JavaScript (minimal, for UI interactions)

## Project Structure

```
sample-question-paper-website/
│
├── index.html          # Main website file (all HTML, CSS, and JS)
├── README.md           # Project documentation
└── assets/             # (Optional) Add images, icons here
    └── preview.png
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic code editor (VS Code, Sublime Text, etc.) for modifications

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/sample-question-paper-website.git
   ```

2. **Navigate to project folder**
   ```bash
   cd sample-question-paper-website
   ```

3. **Open in browser**
   - Simply open `index.html` in your browser
   - Or use Live Server in VS Code for auto-refresh

That's it! No build steps, no dependencies – just open and run.

## Usage

### Customizing Papers

Edit the `.paper-card` articles in the grid section:

```html
<article class="paper-card">
    <span class="paper-tag">MATHEMATICS</span>
    <h3>Your Paper Title</h3>
    <div class="exam-meta">
        <span>Date</span>
        <span>Duration</span>
    </div>
    <p class="description">Your description here.</p>
    <div class="card-footer">
        <span class="meta-light">File info</span>
        <a href="#" class="download-btn">Download</a>
    </div>
</article>
```

### Updating Featured Section

Modify the `.featured-paper` div:

```html
<div class="featured-text">
    <h3>your tag</h3>
    <h2>Main Title</h2>
    <p>Description text</p>
</div>
```

### Changing Colors

The color scheme uses CSS variables in the `style` section. Look for hexadecimal values and gradients to customize:

```css
:root {
    /* Look for colors like #1f3a57, #1e4f77, etc. */
}
```

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Ideas for Contributions

- Add real filter functionality with JavaScript
- Create additional paper category pages
- Implement dark mode toggle
- Add actual PDF download links
- Build a simple backend with paper uploads

## License

This project is licensed under the MIT License – see below for summary:

```
MIT License

Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

## Acknowledgments

- Fonts by [Google Fonts](https://fonts.google.com/)
- Inspiration from modern educational platforms

## Contact

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app
