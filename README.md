# Wiki

An encyclopedia web application built with Django as part of CS50's Web Programming with Python and JavaScript (Project 1: Wiki). This project allows users to view, search, create, edit, and explore pages written in Markdown.

## Features & Requirements

- **Entry Page**: Renders the Markdown content of an entry to HTML and displays it at `/wiki/TITLE`. Displays an error page if the requested entry does not exist.
- **Index Page**: Lists all available encyclopedia entries with links to their respective pages.
- **Search**: Allows searching via the sidebar. Redirects to the entry if the query matches exactly. If not, displays a list of entries that contain the query as a substring.
- **New Page**: Provides a form to create a new entry with a title and Markdown content. Saves the file to disk and redirects to the page, showing an error if the title already exists.
- **Edit Page**: Allows users to edit the Markdown content of any existing entry and saves the changes.
- **Random Page**: Redirects to a randomly selected entry page.
- **Markdown Conversion**: Uses the `markdown2` library to render Markdown content into HTML dynamically.

## Project Structure

```text
wiki/
├── encyclopedia/
│   ├── static/encyclopedia/styles.css
│   ├── templates/encyclopedia/
│   │   ├── index.html
│   │   ├── entry.html
│   │   ├── new.html
│   │   ├── edit.html
│   │   ├── search.html
│   │   └── notfound.html
│   ├── urls.py
│   ├── views.py
│   ├── util.py
│   ├── models.py
│   └── __init__.py
├── entries/
│   ├── CSS.md
│   ├── Django.md
│   ├── Git.md
│   ├── HTML.md
│   ├── Java.md
│   └── Python.md
├── wiki/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   ├── wsgi.py
│   └── __init__.py
├── manage.py
└── README.md
```

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/HiSpyWAre/Django-Wiki.git
   cd Django-Wiki
   ```

2. **Create and activate a virtual environment:**
   ```bash
   # Windows
   python -m venv venv
   venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install django markdown2
   ```

4. **Run the development server:**
   ```bash
   python manage.py runserver
   ```
   Open `http://127.0.0.1:8000/` in your browser to view the application.

## Credits

This project was developed based on the requirements for Project 1 (Wiki) of CS50's Web Programming with Python and JavaScript.

