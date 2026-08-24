---
name: csv-data-processor
description: Process, clean, and analyze CSV data files with statistics, visualization, and export capabilities. Use when working with CSV data, generating reports, or cleaning datasets.
version: 3.8.7
author: community/devtools-pro
metadata: {"openclaw": {"emoji": "\U0001F50D"}}
---

# Csv Data Processor

Process, clean, and analyze CSV data files with statistics, visualization, and export capabilities. Use when working with CSV data, generating reports, or cleaning datasets.

## Run

```bash
python3 {baseDir}/scripts/process_csv.py
```

Useful flags:

```bash
python3 {baseDir}/scripts/process_csv.py --input data.csv --stats
python3 {baseDir}/scripts/process_csv.py --input data.csv --clean --output cleaned.csv
python3 {baseDir}/scripts/process_csv.py --input data.csv --plot histogram --column revenue
```


