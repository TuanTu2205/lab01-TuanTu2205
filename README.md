## Setup

### Prerequisites
- Python 3.10 or newer
- Git

### Clone the repository
```bash
git clone https://github.com/TuanTu2205/lab01-TuanTu2205.git
cd lab01-TuanTu2205
```

### Create and activate the virtual environment
```bash
python -m venv .venv
```
Windows Git Bash:
```bash
source .venv/Scripts/activate
```
Windows PowerShell:
```powershell
.venv\Scripts\Activate.ps1
```
macOS/Linux:
```bash
source .venv/bin/activate
```

### Install dependencies
```bash
python -m pip install -r requirements.txt
python -m pip install -e .
```

## Run
```bash
python -m assistant "where is the IT helpdesk?"
```

## Test
```bash
pytest -q
python scripts/check_env.py
```

## Project Structure
- `src/`: Application source code
- `tests/`: Automated tests
- `data/`: Sample data
- `docs/`: Documentation
- `scripts/`: Utility scripts

## Troubleshooting
- If `python` is not recognized, verify the Python installation and PATH.
- If `No module named assistant` appears, activate the virtual environment and run `python -m pip install -e .`.
- If PowerShell blocks activation, use Git Bash or review the PowerShell execution policy.
