# Pokemon Terastallization Type Analysis

This project analyzes the distribution of Terastallization types used in competitive Pokemon battles on play.pokemonshowdown.com. The data is sourced from Smogon's usage statistics.

## Overview

- Fetches battle data for specified months, years, and competitive tiers
- Aggregates Terastallization type usage across all Pokemon
- Creates visualizations showing:
  - Complete distribution of all Tera types
  - Focused analysis of the top 3 and bottom 3 most used types

## Requirements

- Python 3.x
- Required libraries:
  - requests
  - matplotlib
  - datetime

## Usage

The analysis is contained in a Jupyter notebook (`main.ipynb`) which can be run section by section to:
1. Fetch the latest usage data
2. Process and aggregate type statistics
3. Generate visualizations

## Data Source

Data is retrieved from www.smogon.com/stats