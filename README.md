# RAG and Agentic AI Lab

This repo is a lightweight workspace for the IBM RAG and Agentic AI Professional Certificate.
It focuses on notebooks and exercises, with a simple devcontainer and minimal scaffolding.

## Quickstart (Devcontainer)

1. Open in a devcontainer.
2. The container installs `uv`, creates `.venv`, installs deps, and registers a Jupyter kernel.
3. Start Jupyter:

```bash
.venv/bin/jupyter lab --ip 0.0.0.0 --port 8888 --no-browser
```

Then select the kernel: `Python (rag-agentic)`.

## Local (non-container)

```bash
uv venv
uv pip install -r requirements.txt
python -m ipykernel install --user --name rag-agentic --display-name "Python (rag-agentic)"
```

## Repo Structure

- `notebooks/` notebooks by course/topic
- `exercises/` small, focused tasks (notebook-first)
- `docs/` notes, references, and summaries
- `data/` local datasets (gitignored)

## Environment

Copy `.env.example` to `.env` and add API keys as needed.
