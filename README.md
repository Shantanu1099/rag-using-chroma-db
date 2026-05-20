# RAG-101

Quick guide to run this project.

## Prerequisites

- Python 3.10+
- `pip`
- `uv` - if you want to solely use `uv`

## 1) Clone and open the project

```bash
git clone <your-repo-url>
cd rag-101
```

## 2) Create and activate a virtual environment

### Windows (PowerShell)

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

### macOS/Linux

```bash
python -m venv .venv
source .venv/bin/activate
```

## 3) Install dependencies

### Option A: Using `pip`

```bash
pip install -r requirements.txt
```

### Option B: Using `uv`

```bash
uv pip install -r requirements.txt
```

## 4) Configure environment variables

Create a `.env` file at the **root level** of the project (same level as this `README.md`) and add:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

## 5) Run the project

Use the project entry command (example):

```bash
python main.py
```

If your entry file is different, run that file instead.

## Approach Diagram

There is a picture in `docs` to understand the approach. Example reference:

```text
notes/rag_notes.png
```

If the filename differs, open the image in the `docs/` folder.
