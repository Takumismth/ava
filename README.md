
# Accessible Sign-up Form

A responsive and accessible sign-up form UI created using HTML5 and Sass (SCSS).

## Features

- Full name, email, password and confirm password fields.
- Password visibility toggle UI.
- Password strength progress indicator.
- Password requirements checklist.
- Accessible labels and keyboard focus states.
- Space reserved for validation messages.
- Responsive layout for mobile and desktop.
- Sass variables and nested styles.

## Technologies

- HTML5
- Sass (SCSS)
- npm
- GitHub Pages

## Project Structure

```text
accessible-signup-form/
├── index.html
├── styles/
│   └── main.scss
├── css/
│   └── main.css
├── package.json
├── .gitignore
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Takumismth/ava.git
```

Navigate to the project:

```bash
cd accessible-signup-form
```

Install dependencies:

```bash
npm install
```

Compile Sass:

```bash
npm run build
```

Open `index.html` in your browser.

## Development

To automatically compile Sass whenever you make changes:

```bash
npm run watch
```

## Deployment

1. Push the project to GitHub.
2. Open repository Settings.
3. Select Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the `main` branch and `/ (root)` folder.
6. Save your settings.

Your project will be available at:

https://YOUR_USERNAME.github.io/accessible-signup-form/

## Accessibility

This project includes:

- Semantic HTML elements.
- Explicit labels for form controls.
- Required-field attributes.
- Keyboard-visible focus indicators.
- Accessible progress indicator.
- Descriptive password instructions.
- Reduced-motion support.

## Important Note

This is a static UI project.

The password toggle, progress bar, checklist, and validation messages are visual placeholders. JavaScript can be added later to implement their functionality.

## License

MIT License
