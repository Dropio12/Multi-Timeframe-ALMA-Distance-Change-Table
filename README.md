Here's a README tailored for GitHub:

---

# Multi-Timeframe ALMA Distance & Percentage Change Table

This Pine Script™ indicator calculates and displays the distance between the current price and the ALMA (Arnaud Legoux Moving Average) across multiple timeframes. It also provides an option to show these distances as percentages. Negative values are displayed in red, and positive values are displayed in green.

## Features

- Displays ALMA indicators for up to four different timeframes.
- Calculates the distance from the current price to the ALMA for each selected timeframe.
- Option to display distances as percentages or absolute values.
- Color-coded table where negative values are red and positive values are green.
- Adjustable ALMA parameters including length, offset, and gamma for each timeframe.

## Inputs

- **Timeframes:**
  - `Timeframe 1`: Select the first timeframe.
  - `Timeframe 2`: Select the second timeframe.
  - `Timeframe 3`: Select the third timeframe.
  - `Timeframe 4`: Select the fourth timeframe.

- **ALMA Settings:**
  - `Series`: Select the data series for ALMA calculation (e.g., close, open, high, low).
  - `Length`: ALMA length for each timeframe.
  - `Offset`: ALMA offset for each timeframe.
  - `Gamma`: ALMA gamma for each timeframe.

- **Other Features:**
  - `Display as Percentage`: Toggle between displaying values as percentages or absolute distances.
  - `Decimal Places for Distance`: Number of decimal places for distance values.
  - `Decimal Places for Percentage`: Number of decimal places for percentage values.

## How to Use

1. Adjust the input settings to select the desired timeframes and ALMA parameters.
2. Choose whether to display the distances as percentages or absolute values.
3. Observe the table in the top-right corner of the chart for real-time data.
4. Positive distances will be displayed in green, while negative distances will be displayed in red.

## Example Output

The table will include columns for each selected timeframe and rows for ALMA distances or percentages. Cell colors vary based on whether the value is positive (green) or negative (red).

## Installation

1. Copy the Pine Script™ code provided in this repository.
2. Open TradingView and navigate to the Pine Script™ editor.
3. Paste the copied code into a new script.
4. Save and add the script to your chart.

## Contribution

Feel free to contribute by submitting issues or pull requests. Your feedback and suggestions are welcome!

## License

This Pine Script™ code is subject to the terms of the Mozilla Public License 2.0. See [Mozilla Public License 2.0](https://mozilla.org/MPL/2.0/) for more details.

---

Feel free to adjust or expand any sections to better fit your project's specifics or add any additional information!
