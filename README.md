README.md

# QR-Code-Generator

This is a simple QR code generator web application. It allows you to generate QR codes by entering text and selecting the desired size.

## Usage

1. Open the `index.html` file in a web browser.

2. Enter the text you want to convert into a QR code in the "Enter Your Text" field.

3. Select the desired size for the QR code from the dropdown menu.

4. Click the "Generate" button.

5. The generated QR code will appear below the input fields.

6. You can save the QR code image by right-clicking on it and selecting "Save Image As" or using the appropriate option in your browser.

## Learnings

This QR Code Generator project has provided the following learning opportunities:

1. HTML and CSS: The project involves creating an HTML file with associated CSS styles. You have learned how to structure an HTML file, create elements, use classes and IDs for styling, and apply CSS styles to customize the appearance of the web application.

2. JavaScript: You have learned how to use JavaScript to handle user input and generate dynamic content. The `genQR()` function takes the input text and selected size, constructs a URL for the Google Chart API, and updates the `src` attribute of the `<img>` tag to display the generated QR code.

3. DOM Manipulation: You have learned how to access and modify elements in the HTML document using JavaScript. The `getElementById()` function is used to retrieve the input values and update the QR code image.

4. Google Chart API: The project utilizes the Google Chart API to generate QR codes. You have learned how to construct the API URL with the desired size and input text to generate the QR code image dynamically.

## Resources Used

The following resources were used during the development of this project:

1. Google Chart API: The project relies on the Google Chart API for generating QR codes. You have utilized the API's QR code chart type and customized the URL with desired size and input text. The API documentation and examples provided by Google were used as a reference.

2. HTML and CSS Documentation: Documentation and resources for HTML and CSS were referenced to learn about HTML structure, CSS styles, and layout techniques. Resources like MDN Web Docs (https://developer.mozilla.org) and W3Schools (https://www.w3schools.com) are commonly used references.

3. JavaScript Documentation: JavaScript documentation and resources were referenced to understand concepts like DOM manipulation, handling events, and basic JavaScript syntax. Resources like MDN Web Docs and W3Schools provide comprehensive JavaScript references.

4. Online Tutorials and Examples: Online tutorials and examples related to QR code generation, HTML, CSS, and JavaScript were used as references or sources of inspiration during the development process. Websites like Stack Overflow, CodePen, and various web development blogs are commonly used sources of tutorials and examples.

## Customization

You can customize the styles and appearance of the web application by modifying the CSS code in the `<style>` tag within the `<head>` section of the `index.html` file. Feel free to change colors, font styles, or layout as per your preference.

## Dependencies

This QR code generator does not require any external libraries or dependencies. It uses the Google Chart API to generate the QR code image.

## Compatibility

The web application is designed to work on modern web browsers with JavaScript enabled. It has been tested on the latest versions of Google Chrome, Mozilla Firefox, and Microsoft Edge.

## Author

This QR code generator was developed by Shreya Chakraborty
