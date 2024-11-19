PDF to Images Converter

A web application that allows users to upload a PDF, convert its pages into images, and download the images as a ZIP file. Each image can be previewed, removed, or downloaded collectively.
Features

    PDF Upload: Upload a PDF file to convert its pages to images.
    Image Preview: View the converted images directly in the browser.
    Remove Images: Remove any specific image using the ❌ button.
    Download All Images: Download all remaining images as a ZIP file.

Technologies Used

    HTML5: For creating the structure of the page.
    CSS3: For styling the application.
    JavaScript: For dynamic functionality and interactivity.
    Libraries:
        PDF.js: To render PDF pages as images.
        JSZip: To create ZIP files.
        FileSaver.js: To trigger ZIP file downloads.

How to Use

    Clone the repository or download the code.

    git clone https://github.com/your-username/pdf-to-images-converter.git

    Open the index.html file in any modern web browser.
    Upload a PDF file using the file input.
    Click the Convert button to generate images for each page of the PDF.
    Use the ❌ button to remove unwanted images.
    Click the Download All Images button to download all visible images as a ZIP file.

File Structure

pdf-to-images-converter/
├── index.html        # Main HTML file
├── README.md         # Project documentation
├── js/               # JavaScript libraries (optional if linked via CDN)
│   ├── pdf.js        # PDF.js library (optional)
│   ├── jszip.js      # JSZip library (optional)
│   └── FileSaver.js  # FileSaver.js library (optional)
├── css/              # Custom CSS (if extracted from the HTML)
│   └── styles.css    # Optional stylesheet

Demo

You can view a live demo of this application here: Live Demo Link
(Replace # with the URL if hosted online.)
Screenshots
Upload PDF and Convert

Preview Images with Remove Button

Download All Images as ZIP

License

This project is licensed under the MIT License. See the LICENSE file for details.
Contributions

Contributions are welcome! Feel free to submit a pull request or open an issue for any feature suggestions or bug reports.
