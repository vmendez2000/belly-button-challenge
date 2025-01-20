# belly-button-challenge
# Belly Button Biodiversity Dashboard
### https://vmendez2000.github.io/belly-button-challenge/

## Overview

### The Belly Button Biodiversity Dashboard is an interactive visualization tool that explores bacterial data collected from human belly buttons. This project enables users to analyze the top 10 operational taxonomic units (OTUs) for each test subject and explore demographic metadata.

## Features

## 1. Interactive Bar Chart

* Displays the top 10 OTUs found in a selected individual.

* Uses sample_values for the bar lengths.

* Uses otu_ids as the y-axis labels.

* Includes otu_labels as hover text.

## 2. Bubble Chart

* Visualizes all OTUs in a sample.

* Uses otu_ids for the x-axis values and marker colors.

* Uses sample_values for the y-axis values and marker sizes.

* Includes otu_labels as hover text.

## 3. Metadata Panel

* Displays demographic information for the selected individual.

* Dynamically updates when a new sample is selected.

## 4. Dropdown Menu

* Allows users to select a test subject ID to update the visualizations and metadata dynamically.

## Tools and Technologies

* JavaScript: Core programming language used for logic and interaction.

* D3.js: Fetches data and dynamically manipulates the DOM.

* Plotly.js: Generates the bar and bubble charts.

* HTML/CSS: Provides the structure and styling of the dashboard.

* GitHub Pages: Hosts the deployed application.

## Dataset

The dataset is sourced from Belly Button Biodiversity Data. The JSON file includes:

names: List of test subject IDs.

metadata: Demographic information for each individual.

samples: OTU data for each sample.

## Deployment

The app is deployed on GitHub Pages. You can access it here.

## Installation

### Clone the repository:

* git clone (https://github.com/vmendez2000/belly-button-challenge)

### Navigate to the project directory:

* cd belly-button-challenge

### Open index.html in a browser.

## Usage

### 1.Open the dashboard in your browser.

### 2.Select a test subject ID from the dropdown menu.

### 3.Explore the updated bar chart, bubble chart, and metadata panel.

## Acknowledgments

* Data provided by the Rob Dunn Lab.

* Visualization libraries: D3.js and Plotly.js.

## Resources

### https://robdunnlab.com/projects/belly-button-biodiversity/
### I used ChatGPT to help complete this Challenge
