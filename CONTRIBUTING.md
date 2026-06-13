# Contributing

Thanks for helping improve LLM Agents Radar. This project is intentionally small:
`tracker.py` fetches current GitHub Search API results, rewrites the generated
table in `README.md`, and stores the latest snapshot in `data/items.json`.

## Good First Contributions

- Improve tracker reliability, especially around GitHub API failures or rate limits.
- Add focused tests for `tracker.py` behavior.
- Suggest or implement small table improvements, such as clearer columns or safer text formatting.
- Report data-source issues when the tracker includes projects that do not match the `llm-agent` topic.

## Local Setup

Use Python 3.12 or newer.

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

On macOS or Linux, activate the environment with:

```bash
source .venv/bin/activate
```

## Running The Tracker

```bash
python tracker.py
```

The tracker can run without a token, but anonymous GitHub API requests have a
lower rate limit. To test with a token:

```bash
set GITHUB_TOKEN=your_token_here
python tracker.py
```

On macOS or Linux:

```bash
GITHUB_TOKEN=your_token_here python tracker.py
```

Running the tracker may update both `README.md` and `data/items.json`. Those
files are generated from the current API response, so review the diff before
opening a pull request.

## Pull Request Checklist

- Keep changes focused on one issue or improvement.
- Explain whether your change affects generated data, tracker logic, docs, or workflow behavior.
- If you add tests, include the command you used to run them.
- Do not commit real tokens, local virtual environments, or temporary files.

## Automation Notes

The scheduled update workflow runs every 15 minutes and also runs on manual
dispatch. It installs `requirements.txt`, runs `python tracker.py`, and commits
generated changes only when the tracker output changes.
