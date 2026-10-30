# Project Name: CO₂ per capita emissions comparison between 1950 - 2024 of the 15 countries with higher total CO₂ emissions on 2024

**This project provides a visualization via a Horizon Graph that describes the evolution of the CO₂ emissions per capita for 15 countries with the higher total CO₂ emissions on 2024**

---

## 🚀 Quick Start
You can run the data pipeline using firstly Google Colab to execute the Google Colab Jupyter Notebook and importing the data source file located in the folder data.
The Google Colab Jupyter Notebook will generate an html file index.html that will contain the output visualization.


## 📁 Repository Structure
* `data/` — Contains a link to download the used dataset (`owid-co2-data.csv`) .
* `horizon_co2.ipynb` — Contains the Google Colab Jupyter Notebook (`.ipynb`) used for data processing and HTML generation.
* `index.html` — Contains the output `.html` visualization.

## 📊 Dataset Information
* **Source:** Our World in Data - CO₂ and Greenhouse Gas Emissions Data  ([Link to source](owid-co2-data.csv))
* **Description:** This dataset contains the yearly data for CO₂ emissions metrics for all countries, continents, group of countries, etc. for multiple years

## 🛠️ Execution Guide
Follow these steps to run the pipeline and generate the HTML file:

1. **Open the Notebook:** Import the notebook to Google Colab and open the notebok.
2. **Run All Cells:** Execute the cells sequentially by pressing `Runtime` > `Run all` in the top menu.
3. **Fetch the Data:** The notebook will ask to upload the data file, make sure you download it from the `data/` folder in the repository.
4. **Generate the HTML:** The final cell generates the processed visualizations into a standalone HTML file, which will automatically download to your local machine.

## 🖥️ View the Result
If you just want to see the final output without running any code:
* Download the `index.html` file and open it in any web browser.
* [Optional] View the live interactive version directly on [GitHub Pages](https://victorcalvo25.github.io/co2percapita-horzion-1950-2024/).
