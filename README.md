
# Ablation Monotony Bench (synthetic)

Minimal, reproducible demos that test whether **adding observable information** (under fixed model/hyperparams) can **worsen** expected performance.

## Included demos
- Forecast (AR(3)) — error vs #lags
- Classification (Naive Bayes) — accuracy vs #clues
- Planning (Dijkstra) — regret vs % revealed edges

## How to run
- Open the notebooks in `notebooks/` and Run All (no internet).
- CSV results and charts in `assets/`.
- Try to produce a **stable** non-monotone curve with the same model and evaluation window.

## Contributing
Open an Issue with your **counterexample** (include seeds, CSV, code).

License: MIT
