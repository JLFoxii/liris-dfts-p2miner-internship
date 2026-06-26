# LIRIS Internship - Python Tools for DFTS-P2MINER

This repository presents the work I carried out during my internship at the LIRIS laboratory within the Imagine team, as part of a research project around DFTS-P2MINER.

The internship focused on the development of Python tools to support the preprocessing, visualization and analysis of geospatial time-series data used by DFTS-P2MINER.

## Context

DFTS-P2MINER is a research prototype used to detect and analyze frequent grouped sequential patterns in spatio-temporal geospatial data.

During the internship, I worked on data preparation, automation and visualization tools in order to improve the workflow around this prototype and make the results easier to process and interpret.

## Main Contributions

- Preprocessing of large multi-band GeoTIFF datasets.
- Extraction of temporal bands from geospatial data cubes.
- Handling of missing values and conversion to the format expected by DFTS-P2MINER.
- Geographic cropping of the working area using spatial coordinates.
- Spatial aggregation to reduce processing time on large datasets.
- Automated generation of sigma parameters for DFTS-P2MINER.
- Visualization of raw geospatial images and extracted patterns.
- Automated analysis of DFTS output images.
- Generation of visual exports for Google Earth.
- Exploration of temporal correlation between multiple DFTS executions.

## Technical Environment

The work involved several Python libraries and tools, including:

- Python
- GDAL
- NumPy
- Matplotlib
- Pillow
- PyQt6
- Pandas
- Google Earth
- Linux / Conda environments

## Skills Developed

This internship allowed me to strengthen my skills in:

- geospatial data processing;
- image and raster data manipulation;
- Python scripting and automation;
- exploratory analysis of spatio-temporal data;
- workflow optimization;
- visualization of scientific results;
- research-oriented software development.

## Documents

The repository contains public documents related to the internship:

- `docs/internship-report.pdf` - internship report
- `docs/final-presentation.pdf` - final presentation

## About

This work was carried out during my internship at the LIRIS laboratory, Universite Claude Bernard Lyon 1, within the Imagine team.

The source code of the original research prototype is not included in this repository. This repository is intended as a public presentation of my internship work, contributions and technical skills.
