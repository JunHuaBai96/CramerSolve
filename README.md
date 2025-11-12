# CramerSolve

CramerSolve is a lightweight single-page web app for solving 2-variable linear systems using Cramer's Rule. The interface is designed for quick experimentation in the browser with a clean, step-by-step breakdown of the calculations.



## Features
- Interactive data table for entering coefficients and right-hand-side values.
- Dynamic row management to test multiple scenarios.
- Row selection enables choosing any two equations to solve.
- Detailed calculation log that walks through the determinant computations.
- Instant error feedback for invalid or insufficient input rows.
- Fully client-side implementation with vanilla HTML, CSS, and JavaScript.

## Getting Started
1. Open `CramerSolve.html` in any modern web browser.
2. Adjust the default sample data or add additional rows as needed, then tick the two rows you want to solve.
3. Click **求解** to view the calculated values for `a` and `b`, along with the full derivation steps for the selected rows.

## Usage Tips
- At least two rows are required to compute a unique solution; ensure exactly two rows are selected.
- Mix and match different coefficient sets within the table, then switch selections to compare solutions instantly.
- Click **添加行** to append more scenarios, or **重置** to restore the default sample dataset.

## License
[MIT License](./LICENSE)
