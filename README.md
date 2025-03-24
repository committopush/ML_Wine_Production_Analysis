# Project Dionysus

**Project Dionysus** is an educational time series analysis project focused on modeling and forecasting wine production data from multiple producers.

## Overview

The project demonstrates how to:

- Load and preprocess real-world time series datasets with inconsistent date formats
- Structure reusable, scalable analysis code via object-oriented design
- Generate summary statistics and forecasts using SARIMAX modeling

## Data

Three sample datasets are provided:

- `Almeirim.csv`
- `Benavente.csv`
- `Cartaxo.csv`

Each contains monthly production estimates (in thousands of liters) over a shared time interval. The datasets reflect three distinct formatting styles, representative of future scalability challenges.

## Key Components

- **`Wine` Class**: Encapsulates data loading, validation, reporting, and forecasting logic
- **`report()` Method**: Outputs filtered summary statistics over a user-defined date range
- **`forecast()` Method**: Uses SARIMAX to predict future output and visualize trends
- **Automation**: Automatically processes all CSV files in the /data/ directory

## Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```
