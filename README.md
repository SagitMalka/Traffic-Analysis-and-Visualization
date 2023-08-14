# Packet Analysis and Visualization

This script analyzes packet data stored in CSV files, performs various visualizations, and generates plots to provide insights into packet lengths, delay times, and message size distributions. The analysis involves plotting packet length over time, fitting exponential distributions, calculating Complementary Cumulative Distribution Functions (CCDF), and more.

## Requirements

- Python 3.x
- Required libraries: `numpy`, `matplotlib`, `pandas`

You can install the required libraries using pip:

```bash
pip install numpy matplotlib pandas
```

## Usage

1. Place your CSV files with packet data in the `csv_files` directory.
2. Run the script using Python:

```bash
python packet_analysis.py
```

## Functionality

The script provides the following functionality:

- Plot packet length over time.
- Fit exponential distribution to delay times.
- Plot Probability Density Function (PDF) of delay times.
- Generate Complementary Cumulative Distribution Function (CCDF) plots of message size distributions.
- Save plots in the `plots_png` directory.

## Configuration

- The script automatically deletes existing PNG files in the `plots_png` directory before generating new plots.
- You can customize the behavior by modifying the script variables and functions.

## Notes

- Ensure that your CSV files have the required format with columns such as 'Time', 'Length', 'Protocol', etc., as needed by the script.
- The script automatically generates plots based on the available data and file names.

## License

This script is provided under the [MIT License](LICENSE).

---

Feel free to adapt and modify this README to match your specific needs and project context. Make sure to provide clear instructions for users on how to use the script, what data format it expects, and any other relevant information.
