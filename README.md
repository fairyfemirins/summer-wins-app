# Summer Wins App

A simple app to track and celebrate your accomplishments over the summer (or any period).

## Features
- Add goals (e.g., "Read a book", "Go for a run").
- Increment counters each time you accomplish a goal.
- View your progress.
- Delete goals.

## Note
This repository is published under `fairyfemirins` due to GitHub namespace restrictions. A transfer to `femirins` is pending.

To request a transfer, open an issue in this repository or contact `@femirins` on GitHub.

## Technical Architecture
- **Frontend:** Static HTML/CSS/JS (no framework).
- **Backend:** Flask + SQLite (self-contained, no external dependencies).
- **Database:** SQLite (single file, portable).

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/fairyfemirins/summer-wins-app.git
   cd summer-wins-app
   ```
2. Set up a virtual environment and install dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   python app.py
   ```
4. Open `http://localhost:5000` in your browser.

## Reproducible Tutorial
1. Follow the setup instructions above.
2. Add a goal (e.g., "Meditate for 10 minutes").
3. Click "+1" each time you meditate.
4. Watch your progress grow!

## License
MIT