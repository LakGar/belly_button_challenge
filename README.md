# Belly Button Biodiversity Dashboard 🦠

## Overview

This project visualizes data from the **Belly Button Biodiversity dataset**, which catalogs microbes found in human navels. The goal is to create an interactive dashboard using **D3.js** and **Plotly.js** to explore the dataset, showcasing the top microbial species, sample data, and demographic metadata.

---

## Features

1. **Interactive Bar Chart**:

   - Displays the top 10 OTUs (Operational Taxonomic Units) for a selected individual.
   - Tooltip shows additional information about each OTU.

2. **Bubble Chart**:

   - Visualizes microbial samples with:
     - `otu_ids` for x-axis and marker color.
     - `sample_values` for y-axis and marker size.
     - `otu_labels` for hover text.

3. **Demographic Metadata**:

   - Displays individual demographic information.
   - Updates dynamically when a new sample is selected.

4. **Dynamic Updates**:

   - All visualizations update automatically when a new sample is selected from the dropdown menu.

5. **Deployment**:
   - The dashboard is deployed using GitHub Pages.

---

## How It Works

1. **Bar Chart**:

   - Displays the top 10 OTUs for a selected individual.
   - Uses `sample_values` for bar height, `otu_ids` for labels, and `otu_labels` for hover text.

2. **Bubble Chart**:

   - Each sample is represented as a bubble.
   - Bubble size is determined by `sample_values`.
   - Bubble color corresponds to `otu_ids`.

3. **Metadata Panel**:

   - Displays demographic information of the selected individual.

4. **Dynamic Dropdown**:
   - Choose a sample ID from the dropdown menu to update the charts and metadata.

---

## Deployment

The dashboard is deployed and accessible on **GitHub Pages**.

---

## Credits

Data Source: [Belly Button Biodiversity Dataset](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)  
Frameworks and Libraries:

- **D3.js**
- **Plotly.js**
- **HTML/CSS**

---

## Author

**Your Name**  
[GitHub](https://github.com/your-username)  
[LinkedIn](https://linkedin.com/in/your-linkedin)

---

## License

This project is open source and available under the MIT License.
