# Week 03 — Content Representation & Recommendation Systems

## Environment setup (from scratch)

**1. Install uv** (skip if already installed):
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**2. From the repo root** (`manuscript-critique/`), create the environment and install all dependencies:
```bash
uv python install 3.9      # download Python 3.9 if not present
uv sync                    # creates .venv and installs all packages
```

That's it. `.venv/` is created in the repo root and is used automatically by all `uv run` commands.

## Running notebooks

**Option A — VSCode (recommended)**

1. Install the [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) (`ms-toolsai.jupyter`) in VSCode.
2. Open any `.ipynb` file directly in VSCode.
3. Click **Select Kernel** (top-right of the notebook) → **Python Environments** → choose `.venv` from the repo root.
4. Run cells normally (`Shift+Enter` or `Run All`).

**Option B — browser**
```bash
uv run jupyter notebook teaching-algo-curation/materials/week03_content_representation/
```
Open `module_rec_content_collab_final.ipynb` and run all cells (`Kernel → Restart & Run All`).

No data download needed — the main notebook uses a small contrived dataset defined inline.

## Notebooks

| File | Contents |
|---|---|
| `module_rec_content_collab_final.ipynb` | Content-based + collaborative filtering, distance metrics, prediction, pitfalls |
| `content_based.ipynb` | Extended content-based demo on 25K Spotify tracks |

## Optional: Spotify dataset

`content_based.ipynb` reads from:

```
data/spotify/songs_with_attributes_and_lyrics.csv   # ~955K tracks (not in git)
data/spotify/spotify_sample.parquet                 # cached 25K sample (auto-generated on first run)
```

Place the full CSV at the path above before running that notebook.
