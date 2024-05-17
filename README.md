# Wiki Encyclopedia Web Application

Welcome to the Wiki Encyclopedia Web Application! This project is a simple web application built using Flask, a Python web framework, that serves as a wiki encyclopedia. It allows users to create, read, edit, and search for encyclopedia entries using Markdown syntax.

## Features

- **Entry Page**: Users can visit `/wiki/TITLE` to view the content of a specific encyclopedia entry. If the entry does not exist, an error page is displayed.
- **Index Page**: The index page lists all encyclopedia entries, with each entry name linked to its corresponding page.
- **Search**: Users can search for entries by typing a query into the search box. If the query matches an entry, the user is redirected to that entry's page. Otherwise, a search results page is displayed.
- **New Page**: Users can create a new encyclopedia entry by clicking "Create New Page" in the sidebar. They can enter a title and Markdown content, and upon saving, the entry is added to the encyclopedia.
- **Edit Page**: Each entry page has an "Edit" link that allows users to edit the Markdown content. Changes can be saved, and the user is redirected back to the entry page.
- **Random Page**: Clicking "Random Page" in the sidebar takes the user to a random encyclopedia entry.
- **Markdown to HTML Conversion**: Markdown content is converted to HTML before being displayed to the user, supporting headings, boldface text, unordered lists, links, and paragraphs.

## Installation

1. Clone this repository:
   ```
   git clone <https://github.com/pgatundu/project_1-wiki>
   ```
2. Navigate to the project directory:
   ```
   cd wiki-encyclopedia
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:
   ```
   python app.py
   ```
2. Open a web browser and navigate to `http://localhost:5000` to access the application.

## Directory Structure

- **app.py**: Contains the Flask application code, including route definitions and main functionality.
- **templates/**: Directory containing HTML templates for rendering pages.
- **static/**: Directory containing static assets such as CSS stylesheets and JavaScript files.

## Dependencies

- Flask: Web framework for Python.
- markdown2: Python module for converting Markdown to HTML.

## Contributing

Contributions are welcome! If you have suggestions, feature requests, or bug reports, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project was inspired by the Django web framework's built-in admin interface.
- Special thanks to the Flask and Markdown2 communities for their excellent documentation and resources.
- It was alsopart of my assignments on cs50 Web Programming with Python and JavaScript
