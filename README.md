# PDT: Penguins Dream Team

To use conda environments:
```bash
conda env create -f environment.yaml
conda activate ds
```

To update the existing conda environment:
```bash
conda env update -f environment.yaml --prune
```

To update the environment.yaml file:
```bash
conda env export --no-builds | grep -v "^prefix: " > environment.yaml
```