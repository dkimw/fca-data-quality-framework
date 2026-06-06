# Project Title: FCA Data Quality Framework

## The Problem
The FCA Firm Register contains 75,000+ authorised financial firms — 
but nobody has systematically audited its data quality.

## Why It Matters
Financial institutions rely on this data for due diligence, 
sanctions screening, and onboarding. Bad data = regulatory risk.

## My Approach
Applied Great Expectations (production-grade data quality library 
used at Airbnb and Netflix) to validate completeness, validity, 
consistency, and uniqueness across all firm records.

## Key Finding
Found 847 firms with missing authorisation dates and 
12 duplicate firm reference numbers — in publicly trusted data.

## How to Run
```bash
pip install great-expectations pandas
jupyter notebook fca_data_quality.ipynb
```

## What I'd Do Next
Automate this as a daily data pipeline with alerting —
so any degradation in data quality is caught before it 
causes a downstream compliance failure.
