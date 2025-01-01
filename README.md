# EncoreCSS

**EncoreCSS** is a sharp, modern, simple, and lightweight CSS framework designed to help you build clean and elegant web interfaces with ease. Built with minimalism and usability in mind, it provides a solid foundation for your personal or professional projects.

---

## Features

- **Modern Design**: Sharp and contemporary styles for modern web projects.
- **Lightweight**: Minimal CSS for fast loading and optimal performance.
- **Customizable**: Built with CSS variables for easy theming and customization.
- **Modular**: Organized into separate files for variables, base styles, utilities, and components.

---

## Installation

### Using NPM

Install EncoreCSS via npm:

```bash
npm install encorecss
```

### Using CDN

You can include EncoreCSS directly via a CDN:

```html
<link rel="stylesheet" href="https://unpkg.com/encorecss/index.css" />
```

---

## Usage

### Basic Setup

Add the following to your HTML file:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>EncoreCSS Example</title>
    <link rel="stylesheet" href="path/to/encorecss/index.css" />
  </head>
  <body>
    <h1>Welcome to EncoreCSS</h1>
    <p>Start building with sharp, modern, and simple styles!</p>
  </body>
</html>
```

---

## Components

EncoreCSS provides pre-designed components for quick development:

### Buttons

```html
<button>Primary Button</button>
<button class="secondary">Secondary Button</button>
```

### Cards

```html
<div class="card primary">
  <h4>Primary Card</h4>
  <p>This is a card with a primary background.</p>
</div>

<div class="card secondary">
  <h4>Secondary Card</h4>
  <p>This is a card with a secondary background.</p>
</div>
```

### Utilities

- **Text Utilities**:
  ```html
  <p class="text-white">White Text</p>
  <p class="text-dark">Dark Text</p>
  ```

---

## Folder Structure

EncoreCSS is modular and organized for scalability:

```
encorecss/
├── css/
│   ├── variables.css
│   ├── base.css
│   ├── utilities.css
│   ├── components.css
├── index.css
├── README.md
├── package.json
```

- **`variables.css`**: Global variables for easy theming.
- **`base.css`**: Base styles for HTML elements.
- **`utilities.css`**: Utility classes for quick styling.
- **`components.css`**: Predefined components like buttons and cards.
- **`index.css`**: Combines all files for easy import.

---

## Contributing

Contributions are welcome! If you'd like to improve EncoreCSS or add new features, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add a new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## License

EncoreCSS is licensed under the [MIT License](LICENSE). Feel free to use it for personal or commercial projects.

---

## Author

Created by Ashish Badgujar. For questions or feedback, feel free to reach out at [ashishbadgujar124@gmail.com](mailto:ashishbadgujar124@gmail.com)

---

## Get Started

Start building with **EncoreCSS** and create sharp, modern, and lightweight web interfaces today!
