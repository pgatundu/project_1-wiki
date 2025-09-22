# Wiki
# Django-Based Encyclopedia

## Overview

This project is a simple **Wikipedia-style encyclopedia** built with Django.  
Users can browse entries, search for pages, create new entries using Markdown, edit existing ones, and view random articles.  
It was developed as part of Harvard’s **CS50W Web Programming with Python and JavaScript** course.

## Features

- **Search**: Look up encyclopedia entries by title or partial match.
- **Create New Entry**: Add new pages using Markdown formatting.
- **Edit Entries**: Update existing pages through a Markdown editor.
- **Random Page**: View a random entry at the click of a button.
- **Markdown Rendering**: Content is stored in Markdown and converted to HTML for display.

## File Descriptions

- **encyclopedia/views.py**: Core logic for handling entries, search, create, edit, and random page.
- **encyclopedia/urls.py**: URL routing for all app views.
- **encyclopedia/templates/**:  
  - `index.html`: Displays all entries.  
  - `entry.html`: Shows a single entry (Markdown rendered).  
  - `create.html`: Form for creating new entries.  
  - `edit.html`: Form for editing existing entries.  
  - `search.html`: Displays search results.  
- **util.py**: Helper functions for reading/writing entries in Markdown.

## Setup

To run this project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/pgatundu/project_1-wiki.git
cd project_1-wiki

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the server
python manage.py runserver
