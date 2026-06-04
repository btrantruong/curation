# Week 03 — Content Representation & Recommendation Systems

## Setup

Requires [uv](https://docs.astral.sh/uv/getting-started/installation/).

From the **repo root** (`manuscript-critique/`):

```bash
uv sync
```

This installs all dependencies (numpy, pandas, scikit-learn, matplotlib, ipykernel, etc.) into a local `.venv`.

## Running the notebook

```bash
uv run jupyter notebook teaching-algo-curation/materials/week03_content_representation/
```

Then open `module_rec_content_collab.ipynb` in the browser. Run all cells top-to-bottom (`Kernel → Restart & Run All`).

No data download needed — the notebook uses a small contrived dataset defined inline.

## Notebooks

| File | Contents |
|---|---|
| `module_rec_content_collab.ipynb` | Content-based + collaborative filtering, distance metrics, pitfalls |
| `module2_teaching_plan_with_simulation.ipynb` | Extended content-based demo on 25K Spotify tracks |

## Optional: Spotify dataset

`module2_teaching_plan_with_simulation.ipynb` reads from:

```
data/spotify/songs_with_attributes_and_lyrics.csv   # ~955K tracks (not included)
data/spotify/spotify_sample.parquet                 # cached 25K sample (auto-generated on first run)
```

The full CSV is not tracked in git. Place it at the path above before running that notebook.
