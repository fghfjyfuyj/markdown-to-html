# Markdown to HTML Converter

This project provides a simple, single-page web application that converts a Markdown file (`input.md`) into HTML and renders it dynamically in the browser. It leverages Tailwind CSS for responsive styling and `marked.js` for efficient Markdown parsing.

## Features

*   **Dynamic Markdown Conversion**: Automatically fetches `input.md` and converts its content to HTML using `marked.js`.
*   **Responsive Design**: Built with Tailwind CSS, ensuring a clean and adaptive layout across various screen sizes.
*   **Single-File Application**: All core logic and styling are contained within `index.html` for easy deployment and sharing.
*   **Easy to Use**: Just place `input.md` in the same directory as `index.html` and open the HTML file in your browser.

## Getting Started

To get this application running locally, follow these simple steps:

1.  **Save the Files**: Ensure `index.html` and `input.md` are saved in the same directory on your computer.
2.  **Prepare `input.md`**: Create or place your Markdown content within the `input.md` file.
3.  **Open `index.html`**: Double-click `index.html` in your file explorer, or open it with your preferred web browser.

The application will automatically fetch the content from `input.md`, convert it to HTML, and display it on the page.

## Technologies Used

*   **HTML5**: For the basic structure of the web page.
*   **Tailwind CSS**: A utility-first CSS framework for styling and responsiveness.
*   **Marked.js**: A full-featured markdown parser and compiler written in JavaScript.

## Customization

*   **Styling**: Modify the Tailwind CSS classes directly within `index.html` or extend them with custom CSS if needed.
*   **Markdown Source**: To use a different Markdown file, change `'input.md'` in the JavaScript `fetch` call within `index.html`.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.
