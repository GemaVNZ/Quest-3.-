# Way to Paris - Carbon Emission Analysis

![CO2 Emissions GIF](https://media.giphy.com/media/HwvXsuDiQLaiQ/giphy.gif?cid=790b7611c3xqu4e7dnajiwk8i6icygnq9l7wum78bcsn62nk&ep=v1_gifs_search&rid=giphy.gif)

## Table of Contents 📑
- [Overview 🌍](#overview)
- [Installation 🔧](#installation)
- [Usage 🚀](#usage)
- [Project Structure 🏗️](#project-structure)
- [Data Sources 📊](#data-sources)
- [Contributing 🤝](#contributing)
- [Contact 📬](#contact)

## Overview 🌍
This project aims to analyze carbon emissions for various travel options from Madrid to Paris. It leverages data analysis and visualization tools to provide insights into the most environmentally friendly travel choices.

## Installation 🔧
To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/GemaVNZ/Way-to-Paris-Carbon-Emission-Analysis-.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Way-to-Paris-Carbon-Emission-Analysis-
    ```
3. **Install the necessary dependencies:**
    ```bash
    pip install requests pandas json seaborn matplotlib
    ```

## Usage 🚀
To analyze CO₂ emissions and related data, follow these steps:

1. **Data Preparation**:
   - Ensure that the necessary CSV files are in the `Data CSV/` folder:
     - `data_CodePostal.csv` – Contains data on postal codes.
     - `data_chargesmap.csv` – Contains information on charging station locations.
     - `vehicle_emissions_data.csv` – Contains vehicle emissions data for various models and types.

2. **Running the Notebooks**:
   - Navigate to the `Data Analysis and Cleaning/` folder to use the Jupyter Notebooks:
     - **Analisis_CO2.ipynb**: Analyzes CO₂ emissions data from various sources.
     - **DataChargeMap.ipynb**: Processes and visualizes data on charging station locations, useful for identifying charging infrastructure coverage.
     - **ProyectoCO2.ipynb**: Main project notebook that integrates multiple data sources and performs comprehensive CO₂ emission analysis.
     - **Vuelos_CO2.ipynb**: Specifically focuses on CO₂ emissions from flights, allowing comparisons across different routes and transportation methods.

3. **API Documentation**:
   - Refer to `Carbon Interface_API Docs.pdf` for information on using the Carbon Interface API. This API documentation provides guidelines for integrating real-time emissions data into the analysis.

4. **Generating Insights**:
   - Each notebook is structured to walk through the data cleaning, analysis, and visualization stages.
   - Review the generated plots and summaries in each notebook to gain insights into CO₂ emissions and charging infrastructure.

5. **Interpreting Results**:
   - Use the insights obtained to assess emission levels across different transport modes and locations, focusing on areas such as train, car, and flight emissions.

## Project Structure 📂

- **Data CSV**:
  - `data_CodePostal.csv`: CSV file containing postal code data.
  - `data_chargesmap.csv`: CSV file with charging station map data.
  - `vehicle_emissions_data.csv`: CSV file with vehicle emissions data.

- **Data Analysis and Cleaning**:
  - `Analisis_CO2.ipynb`: Jupyter Notebook for CO2 analysis.
  - `DataChargeMap.ipynb`: Jupyter Notebook for analyzing charging station data.
  - `ProyectoCO2.ipynb`: Jupyter Notebook for the main CO2 project analysis.
  - `Vuelos_CO2.ipynb`: Jupyter Notebook for analyzing flight CO2 emissions.

 - **PDFs**: Project presentation in PDF format.
    - `presentation.pdf`: Project presentation in PDF format.
    - `Carbon Interface_API Docs.pdf`: PDF documentation for the Carbon Interface API.


- `README.md`: File to describe the project and how to set it up.
 
## Data Sources 📊
- **Carbon Interface API**: [Carbon API Web](https://www.carboninterface.com/)
- **Open Charge Map API**: [Open Charge API Web](https://openchargemap.org/)

## Contributing 🤝
We welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## Contact 📬
For any questions, feel free to reach out to Gema, Laura, or Miqueas at:

| Name            | GitHub Profile                             |
|-----------------|--------------------------------------------|
| Gema Villena    | [Gema](https://github.com/GemaVNZ)         |
| Laura Sanchez   | [Laura](https://github.com/laurasanchez20) |
| Miqueas Molina  | [Miqueas](https://github.com/miqueasmd)    |
