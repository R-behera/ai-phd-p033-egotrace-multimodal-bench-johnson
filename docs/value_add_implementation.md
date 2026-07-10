# Value-Add Implementation

This repo now includes runnable starter code, not only a project name.

## What The Code Does

- Loads professor-specific metadata from `data/advisor_profile.json`.
- Loads a small seed dataset from `data/value_add_examples.csv`.
- Runs a category-specific audit for `vision` research.
- Produces JSON metrics that can be committed into `reports/demo_results.json`.

## Run It

```bash
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```

## How This Adds Value

For **Justin Johnson**, the starter artifact is: **distribution-shift and failure-analysis benchmark for vision/multimodal models**.

The immediate next contribution is: Replace seed cases with public/lab visual examples and run one real pretrained baseline.

## What To Replace Before Emailing Results

The sample CSV proves the code path works. Before claiming research output, replace the seed rows with current papers, public benchmark outputs, or approved lab-relevant data.
