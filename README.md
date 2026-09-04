# AI Task Router Agent

This project is a Jupyter Notebook demo of a simple AI agent that understands a user's request, classifies the intent, and routes it to the right tool.

## What The Agent Can Do

- Manage schedule requests by creating, updating, deleting, and checking event conflicts.
- Look up basic location information using the Open-Meteo geocoding API.
- Run simple analytics on a list of numbers, including average, maximum, minimum, and count.

## Project Files

- `agent.ipynb` - main notebook containing the agent logic.
- `Task 2 (AI Agent).pdf` - project/task reference document.
- `requirements.txt` - Python dependencies needed to run the notebook.

## Setup

1. Create and activate a virtual environment.

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Install dependencies.

```bash
pip install -r requirements.txt
```

3. Create a `.env` file with your API key.

```bash
API_KEY=your_api_key_here
```

4. Open and run `agent.ipynb` in Jupyter Notebook or VS Code.

## Notes

The `.env` file and local virtual environment are intentionally ignored so credentials and installed packages are not committed to the repository.
