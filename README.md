# News Article Classification

## Setup

1. Open a terminal in the `News Article` folder.
2. Create and activate the virtual environment:
   - `python -m venv .venv`
   - `.
venv\Scripts\activate`
3. Install dependencies:
   - `pip install -r requirements.txt`

## Run

1. In the same folder, run:
   - `python server.py`
2. Open the app in your browser:
   - `http://localhost:8000/`

## Notes

- The app uses `model.pkl` and `vectorizer.pkl` from the current directory.
- If you restart the terminal, reactivate the virtual environment before running `server.py`.
