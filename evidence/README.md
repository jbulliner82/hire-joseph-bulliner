# Joseph Bulliner — Evidence Lab

**Published:** October 18, 2026. **Status:** working independent career-portfolio demonstrations, not employer work or production deployments.

## Try the interactive work
- [Evidence Lab landing page](index.html)
- [Parcel Evidence Lab](parcel-lab.html) — eight fictional properties, filtering, source-gap checklist, deterministic score and JSON export.
- [Leadership Under Pressure](learning-lab.html) — three decision scenarios with answer feedback, score and retake.

## Reproduce the technical results
- [Automation source and instructions](automation/)
- [Python source](automation/clean_pipeline.py)
- [Ten unit tests](automation/tests/test_clean_pipeline.py)
- [Seeded synthetic dataset](automation/data/sample_leads.csv)
- [Baseline QA report](automation/results/qa_report.json)

Local verification on the seeded dataset: **240 rows processed; 187 accepted; 53 quarantined; 10 pytest tests passed.** A GitHub Actions test workflow is configured at [.github/workflows/evidence-qa.yml](../.github/workflows/evidence-qa.yml); check its actual run status before claiming hosted CI success.

## Documentation
- [Instructional design / outcomes alignment and evaluation plan](docs/LEARNING_DESIGN_CASE_STUDY.md)
- [Technical case studies and evidence boundaries](docs/TECHNICAL_CASE_STUDIES.md)
- [Existing ShowUp ML prototype](https://github.com/jbulliner82/showup-appointment-predictor)

## Important limits
All new property and pipeline data is **fictional/synthetic**. These demos do not validate actual parcel conditions, employee learning gains, enterprise production use, customer adoption, business savings, or clinical impact. Browser screenshots and updated application-specific resumes are in the downloadable career-portfolio package prepared October 2026.

**Author:** Joseph Bulliner · [GitHub profile](https://github.com/jbulliner82) · [Professional hiring site](https://jbulliner82.github.io/hire-joseph-bulliner/)
