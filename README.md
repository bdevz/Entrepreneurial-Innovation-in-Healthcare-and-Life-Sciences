# Guardant Shield Market Share Projection

## Overview

This project calculates and projects the market share for Guardant Shield, a blood-based colorectal cancer (CRC) screening test, from 2025 to 2030. The projection uses the Bass Diffusion Model combined with insights from a Conjoint Analysis to provide a pragmatic forecast of market adoption.

## Features

- Implements the Bass Diffusion Model for technology adoption forecasting
- Incorporates importance weights from Conjoint Analysis
- Calculates yearly market share projections
- Outputs results in a clear, tabular format

## Requirements

- Python 3.7+
- NumPy
- Pandas

text

2. Navigate to the project directory:

cd guardant-shield-projection
text

3. Install the required packages:

pip install numpy pandas
text

## Usage

Run the script using Python:


python market_share_projection.py
text

The program will output a table showing the projected market share for Guardant Shield from 2025 to 2030.

## Model Parameters

- Coefficient of innovation (p): 0.03
- Coefficient of imitation (q): 0.38
- Total potential users: 7,500,000
- Target market share by year 7: 23%

## Importance Weights (from Conjoint Analysis)

- Sensitivity: 40% importance
- Convenience: 25% importance
- Trust in Brand: 20% importance
- Insurance Coverage: 10% importance
- Cost: -15% importance (negative, indicating a barrier)

## Output

The program generates a table with the following columns:
- Year
- Guardant Shield Market Share (%)

## Limitations

- The model assumes relatively stable market conditions
- Actual market share may vary based on unforeseen factors or market disruptions
- The projection is based on current data and assumptions, which may change over time

## Contributing

Contributions to improve the model or extend its capabilities are welcome. Please submit a pull request or open an issue to discuss proposed changes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
