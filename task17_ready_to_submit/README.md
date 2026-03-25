# Django Sticky Notes Application Part 2

## Project contents
- `diagrams/` - design diagrams
- `sticky_notes_app/` - final Django project source code
- `sticky_github.txt` - public GitHub repository link
- `requirements.txt` - project dependency list

## Setup
1. Open a terminal.
2. Change into the Django project folder:
   ```bash
   cd sticky_notes_app
   ```
3. Create and activate a virtual environment.
4. Install dependencies:
   ```bash
   pip install -r ../requirements.txt
   ```
5. Run migrations:
   ```bash
   python manage.py migrate
   ```
6. Start the server:
   ```bash
   python manage.py runserver
   ```
7. Open the application homepage at:
   ```
   http://127.0.0.1:8000/
   ```

## Run tests
From inside `sticky_notes_app` run:
```bash
python manage.py test notes
```
