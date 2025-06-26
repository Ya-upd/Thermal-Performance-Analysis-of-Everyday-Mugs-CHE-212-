# Thermal Performance Comparison: Ceramic vs. Vacuum-Insulated Mugs

## Overview

This repository contains all materials for an innovation experiment conducted as part of CHE 212. The project investigates and compares the heat retention capabilities of ceramic and vacuum-insulated mugs using hands-on experimentation, sensor data analysis, and theoretical modeling.

## Contents

- `Presentation.pdf`  
  Slide deck summarizing the experiment, methodology, results, and conclusions.

- `lumped_vacuum_mug.m`  
  MATLAB script implementing the lumped-capacitance model to analyze the vacuum mug's thermal response.

- `normal_mug.txt`  
  Raw temperature data from the ceramic mug (inner and outer wall sensors).

- `vacuum_mug.txt`  
  Raw temperature data from the vacuum-insulated mug (inner and outer wall sensors).

## Project Description

- **Objective:**  
  Experimentally compare the heat retention of ceramic and vacuum-insulated mugs, and validate theoretical heat transfer models.

- **Approach:**  
  - Installed thermocouples on both mugs' inner and outer surfaces.
  - Poured hot water and logged temperature data over time.
  - Analyzed results using MATLAB and theoretical models (Newton’s law of cooling, lumped-capacitance analysis).

- **Key Results:**  
  - Vacuum-insulated mug exhibited significantly better heat retention than the ceramic mug.
  - Experimental data closely matched theoretical predictions, providing insights for improved thermal container design.

## Usage

1. **Presentation:**  
   Review `Presentation.pdf` for an overview of the project and findings.

2. **Data Files:**  
   - `normal_mug.txt` and `vacuum_mug.txt` contain time-stamped temperature readings from both mugs.
   - Use these files for your own analysis or to reproduce results.

3. **MATLAB Analysis:**  
   - Open `lumped_vacuum_mug.m` in MATLAB.
   - Load the `vacuum_mug.txt` dataset as directed in the script.
   - Run the script to perform lumped-capacitance modeling and visualize the results.

