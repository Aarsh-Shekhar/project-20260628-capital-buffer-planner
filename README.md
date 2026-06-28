# Capital Buffer Planner

Stress tests synthetic capital buffers under scenarios.

## What it includes

- deterministic sample data
- scoring and ranking logic
- command line report
- unit tests
- continuous validation workflow

## Run

```bash
python3 -m capital_buffer_planner.cli --input data/sample_scenarios.json
```

## Test

```bash
python3 -m unittest discover tests
```
