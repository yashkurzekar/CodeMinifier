# VF Code Minifier

A lightweight web-based tool for minifying Visualforce (VF) code or any other HTML, JavaScript, or CSS code. This application removes unnecessary spaces, line breaks, and comments to make your code compact and efficient.

## Features

- **User-Friendly Interface:** Simple and clean design for easy usage.
- **Code Minification:** Removes comments, extra spaces, and line breaks to generate a minified version of your code.
- **Copy Functionality:** Copy the minified code to the clipboard with a single click.
- **Responsive Design:** Works seamlessly on devices of all sizes.

## How to Use

1. Clone this repository or download the files:
   ```bash
   git clone <repository-url>
   ```

2. Open the `index.html` file in your browser.

3. Paste your code into the **Input Your Code** text area.

4. Click the **Minify Code** button to generate the minified code.

5. Copy the minified code using the **Copy Minified Code** button.

## Code Breakdown

### HTML Structure
- The layout consists of:
  - **Title Section**: Displays the title of the tool.
  - **Input Section**: A text area for users to paste their code.
  - **Output Section**: A text area to display the minified code, with a button to copy it.

### CSS Styling
- Clean and modern styling with:
  - Rounded corners for containers and buttons.
  - Shadow effects for a subtle 3D look.
  - Focus highlights for better user interaction.

### JavaScript Functionality
- **Minify Code:**
  - Removes single-line (`//`) and multi-line (`/* */`) comments.
  - Reduces multiple spaces to a single space.
  - Removes unnecessary line breaks.
- **Copy to Clipboard:**
  - Allows users to copy the minified code to the clipboard for easy reuse.

## Example
### Input Code
```html
<!-- Sample HTML Code -->
<div>
    <h1> Hello, World! </h1>
    <p> This is a test. </p>
</div>
```

### Minified Code
```html
<div><h1>Hello, World!</h1><p>This is a test.</p></div>
```

## Future Enhancements
- Support for more advanced minification.
- Add an option to minify specific file types (e.g., JavaScript or CSS).
- Provide downloadable minified files.

## Credits
Developed by [Yash Kurzekar](#).

## License
This project is licensed under the MIT License. Feel free to use and modify it as needed.
