# Data quality automation — reproducible portfolio test

**Owner:** Joseph Bulliner. **Status:** independent demonstration, not deployed to an employer. All records are synthetic.

Run with Python 3.11+:

```bash
cd evidence/automation
python clean_pipeline.py --input data/sample_leads.csv --out results
python -m pip install pytest
python -m pytest -q
```

Expected dataset summary (seeded 240 rows): 187 accepted, 53 quarantined, with 7 duplicate IDs, 22 invalid emails, 11 invalid priority labels, and 13 unsupported sources. The test suite contains ten checks.

Output files: `results/cleaned.csv`, `results/quarantine.csv`, `results/qa_report.json`. The baseline `results/qa_report.json` is committed for reproducibility.

This validates input quality rules and exception accounting. It **does not demonstrate** production deployment, client results, real-world time savings, or integration with a live service.
