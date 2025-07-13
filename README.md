## MjÖlnir
A streamlined tool for visualizing any 2D dataset without writing repetitive Python or MATLAB code. Analyze data on the fly, save project in one place, and eliminate cluttered scripts and image files. By reducing workflow complexity, a data can not just seen but better understood.
# What is it made for?
While the purpose of the built is for 2D infrared spectroscopy, this tool adapts seamlessly to any excitation-emission or two-dimensional datasets from fluorescence spectra to electronic spectra. 

# Core Analytical Features
# Smart Peak Detection
Laplacian-based algorithm identifies peaks even in noisy spectra
Adjustable sensitivity for precise localization

# Cross-Section Analysis
Extract and fit slices along both pump and probe axes
Compare multiple slices with overlay plotting

# Automatic Baseline Correction
Spline-based removal of background artifacts
Visual verification of correction quality

# Publication-Ready Output
One-click export in vector formats (PDF/SVG)
Customizable fonts, axis labels, and color scales
Optional gridlines/ticks matching journal guidelines

# Data import
As there is always debates about the way of representation of a 2DIR or 2D electronic data (X axis pump or probe), the data importation is not of wide range.This tool requires 2D spectral data in a standardized matrix format for unambiguous analysis: The first row must contain the probe/X-axis values, the first column must contain the pump/Y-axis values, and the remaining cells should contain the Z-data aligned with these dimensions. Files must use commas (,) as delimiters and periods (.) as decimal separators (e.g., "1950.5") to ensure consistent interpretation across different regional

