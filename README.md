# URL SHORTENER

A self-hosted URL shortener built with (Python) Flask and SQLite.

## Features
- Shorten any long URL into a 6-character code (length is adjustable)
- Local SQLite database for storage
- Statistics page showing all saved links
- Modern style UI with custom css styling
- Auto-adds `https://` if missing
- SQL-injection safe (parameterized queries)
- Auto-generates database on first run
- Live reload during development (`debug=True`)

## How It Works
1. You enter a long URL in the form
2. The app generates a unique 6-character code
3. The code + original URL are saved in the SQLite database

## Usage
terminal:
```
pip install flask
python urlShortener.py
```

Then open your browser at: http://localhost:5000/ and have fun with the tool!
