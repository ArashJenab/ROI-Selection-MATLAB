# Select and Export Region of Interest (ROI) From a Large Data Set Using MATLAB / Octave

## Overview

This repository provides MATLAB and Octave scripts for selecting and exporting Regions of Interest (ROIs) from large data sets. The method utilizes the `ginput` function, allowing users to manually define selection points and extract corresponding data for further analysis.

This is useful when:

- You need to process only a portion of a large dataset.
- You want to exclude unnecessary data points before analysis.
- You are analyzing experimental data and need to focus on specific segments.

## Features

- Interactive selection of regions using mouse input.
- Works with both **MATLAB** and **GNU Octave**.
- Exports selected regions as separate files.
- Saves extracted data in both **MATLAB (.mat)** and **PDF formats**.

## Requirements

- **MATLAB** (Recommended) or **GNU Octave**
- Basic understanding of MATLAB scripting.

## Installation

1. Download or clone this repository:
   ```bash
   git clone https://github.com/ArashJenab/ROI-Selection-MATLAB.git
   ```
2. Extract the files if downloaded as a ZIP.
3. Open MATLAB or Octave and navigate to the script's directory.

## Usage

1. Load the sample data provided or your own dataset.
2. Run the script:
   ```matlab
   run('ROI_Selection.m')
   ```
3. A plot of your dataset will appear.
4. Click two points to define the start and end of the desired region.
5. The selected region will be saved automatically in a folder named `Exported_ROIs`.
6. Repeat the process for additional selections if needed.
7. Review the saved `MAT` files or PDF plots for your selected regions.

## Example Applications

- Data filtering for **signal processing**.
- Selecting specific events in **experimental physics**.
- Extracting relevant data from **tensile/compression tests**.

## File Structure

- `ROI_Selection.m` - Main script for selecting and exporting data.
- `SampleData/` - Example datasets for testing.
- `Exported_ROIs/` - Folder where selected regions are saved.

## Video Tutorial

Watch the full tutorial on YouTube: [Select and Export ROI Tutorial](https://www.youtube.com/watch?v=FUi6Pmdxbig)

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute it as needed.

## Author

Developed by **Arash Jenab**

For more details and additional resources, visit: [www.arashjenab.com](http://www.arashjenab.com)

---

Feel free to contribute to this project by submitting pull requests or opening issues for feature requests and bug fixes.
