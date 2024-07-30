---

# Text to Handwriting Flask Application

This is a simple Flask web application that converts text input into a series of corresponding handwritten images. Each character in the input text is mapped to a specific handwritten image file.

## Features

- Accepts user input via a web form.
- Converts each character in the input text to a corresponding handwritten image.
- Supports letters, punctuation, and some special characters.
- Displays the sequence of images representing the input text in handwritten form.

## Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- Python 3.6+
- Flask

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/saiadupa/text-to-hand-writing.git
    cd text-to-hand-writing
    ```

2. **Create and activate a virtual environment:**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```sh
    pip install Flask
    ```

### Running the Application

1. **Start the Flask application:**

    ```sh
    python app.py
    ```

2. **Open your web browser and navigate to:**

    ```
    http://127.0.0.1:5000/
    ```

## Project Structure

```plaintext
.
├── static
│   ├── a.png
│   ├── Aupper.png
│   ├── qmark.png
│   ├── slash.png
│   ├── colon.png
│   ├── dot.png
│   ├── _(1).png
│   ├── ,..png
│   ├── space.png
│   ├── semicolon.png
│   ├── ...
│   └── ... (other image files)
├── templates
│   ├── index.html
│   └── output.html
├── app.py
└── README.md
```

- **static/**: Contains the handwritten image files for each character.
- **templates/**: Contains the HTML templates for rendering the web pages.
  - `index.html`: The main page with the input form.
  - `output.html`: The page that displays the sequence of handwritten images.
- **app.py**: The Flask application.

## Usage

1. Navigate to the main page.
2. Enter your text in the input form.
3. Submit the form to see the corresponding handwritten images.

## Examples

For example, if you enter the text `Hello World!`, the application will display the following handwritten images:

- `Hupper.png`
- `e.png`
- `l.png`
- `l.png`
- `o.png`
- `space.png`
- `Wupper.png`
- `o.png`
- `r.png`
- `l.png`
- `d.png`
- `!.png`

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Acknowledgements

- Flask documentation: [Flask](https://flask.palletsprojects.com/)
- Python documentation: [Python](https://www.python.org/doc/)

---


<a href="https://www.buymeacoffee.com/nithinsaiadupa" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
