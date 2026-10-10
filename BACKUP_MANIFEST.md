# Excluded local files and data

The source workspace contains files intentionally omitted from this public repository:

- `data/competition_starter/`: raw challenge dataset and sample files (dataset redistribution rights may be limited).
- `runs/`: generated training outputs and model checkpoints.
- `models/`: local model artifacts.
- `submissions/`: generated submission files.
- `.venv/`: local Python environment.
- `config/config.yaml`: private local override, excluded by `.gitignore`.
- `.kaggle/` and Kaggle credential files: account credentials, excluded by `.gitignore`.

The source `.gitignore` excludes these data, generated output, environment, and credential paths. Check the cluster directories before deletion if any of these need a separate backup.
