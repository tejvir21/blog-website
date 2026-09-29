# BlogWebsite

This is a simple blog website project developed using Flask, HTML, CSS, and JavaScript.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/tejvir21/blog-website.git
    ```
2. Navigate to the project directory:
    ```bash
    cd blog-website
    ```
3. Create a virtual environment:
    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
5. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
6. Run the Flask application:
    ```bash
    flask run
    ```
7. Open your web browser and go to `http://127.0.0.1:5000` to view the website.

## Usage

- Add your blog posts in the `posts` directory.
- Update the `index.html` file to include links to your new posts.
- Customize the styles in the `static/styles.css` file.
- Modify the Flask routes in `server.py` to handle new pages or features.

## Features

- Responsive design
- Easy to add new blog posts
- Simple and clean layout

## Contributing

We welcome contributions to enhance the BlogWebsite project. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Description of your changes"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Open a pull request describing your changes.

Please ensure your code follows the project's coding standards and includes appropriate tests.

Thank you for your contributions!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
