# Shared code structure

To ensure clarity, reproducibility, and collaboration, all our projects follow a consistent structure inspired by industry and academic best practices.

## Example Layout

```bash
project-name/
├── src/                # core Python code
├── results/
├── scripts/            # scripts and notebooks
├── data/               # local data (often gitignored)
├── docs/               # extra documentation
├── environment.yml     # conda environment
├── README.md           # project overview
└── .gitignore
```

Make sure to always include a README.md with:

- project purpose
- installation
- example usage
- how to contribute

## Why this structure?

You will see that I am  not always the best at following this structure and completing my README.me files. However, it is really useful to actually be consistent for the following reasons:

- Clear separation of code, data, and experiments
- A consistent structure is easier for newcomers to navigate
- This structure is compatible with tools liek pytest, and linters
- It simplifies things for when we want to publish our repositories
