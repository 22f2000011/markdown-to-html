# Markdown to HTML Converter

This is a simple, single-file web application that converts Markdown content from `input.md` into rendered HTML directly in the browser. It leverages **Tailwind CSS** for responsive styling and **Marked.js** for efficient Markdown parsing.

## Features

-   **Live Markdown Conversion**: Automatically fetches `input.md` and renders it as HTML.
-   **Responsive Design**: Built with Tailwind CSS to look great on any device.
-   **Single File**: All logic and styling are contained within `index.html` for easy deployment.
-   **Client-Side**: No server-side processing required.

## Usage

1.  **Place `input.md`**: Ensure your Markdown file is named `input.md` and is located in the same directory as `index.html`.
2.  **Open `index.html`**: Simply open `index.html` in your web browser. The content of `input.md` will be displayed as rendered HTML.

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS (CDN)**: For utility-first styling and responsive design.
-   **Marked.js (CDN)**: A fast Markdown parser and compiler for JavaScript.

## Customization

To change the Markdown content, simply edit the `input.md` file. The `index.html` will automatically pick up the new content upon refresh.
For custom styling, you can modify the Tailwind classes directly in the `index.html`'s inline script section where elements are styled after markdown conversion, or override them with custom CSS.

## License

This project is open-source and available under the MIT License.