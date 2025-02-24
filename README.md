# README.md

# Venmito Data Engineering Project

## Overview.

**Author:**            Ignacio Sadurni

**Email:**               ignaciosadurni@gmail.com

**Description:**    This project aims to create value for a hypothetical company ‘Venmito’. Disparate data sources were cleaned and consolidated into a format that would make it possible to create visualizations and inspire meaningful insights for their business operations, as well as a permanent solution for the collection, organization, and consumption of their available data.

## Getting Started.

*Step-by-step instructions to download and interact with source code and dashboard.*

**Running Code:**

1. Download `venmito_data_exploration.ipynb` located at `/code` .
2. Open the file in Google Colab (or your preferred editor that supports Python notebooks at your discretion).
3. Download the following files from `/data/raw` :
    - `people.json`
    - `people.yml`
    - `promotions.csv`
    - `transactions.xml`
    - `transfers.csv`
4. Select the file icon in the left toolbar and upload these in the opened directory (`/content`).
5. Click ‘Runtime’ → ‘Run All’ in the top toolbar.
    1. You can also run these cell individually to view the progression of the data processing, but it is very important to run each cell in order and only once.
    2. I recommend having the table of contents opened on the left so you understand what stage of the data gathering/analysis process you are viewing.
6. You should be able to view the data frames and visualizations, now you can access the processed files in `/content`  (these are also saved in the GitHub repository `/data/processed`).

**Viewing Dashboard:**

- Video Tour *~recommended*
    - Watch this [video](https://drive.google.com/file/d/1FrHBAXtPiKPMgd5lb5iXdvSrckGWPz8f/view?usp=sharing) to learn about the dashboard.
    - [https://drive.google.com/file/d/1FrHBAXtPiKPMgd5lb5iXdvSrckGWPz8f/view?usp=sharing](https://drive.google.com/file/d/1FrHBAXtPiKPMgd5lb5iXdvSrckGWPz8f/view?usp=sharing)
- Interactive Dashboard
    - Using the following link you can open the dashboard in Tableau Online:
    - [https://prod-uk-a.online.tableau.com/t/ignaciosadurni-2444af8137/views/Transactions/SalesInsights?:origin=card_share_link&:embed=n](https://prod-uk-a.online.tableau.com/t/ignaciosadurni-2444af8137/views/Transactions/SalesInsights?:origin=card_share_link&:embed=n)
- Static Dashboard
    - Open .pdf file
    - This version does not support filters and sorting functions and will show static/non-interactive data.

## File Structure.

*GitHub file routing*

- `venmito-isadurni/`
    - `data/`
        - `raw/`
            - `people.json`
            - `people.yml`
            - `promotions.csv`
            - `transactions.xml`
            - `transfers.csv`
        - `processed/`
            - `item_sales.csv`
            - `peopleclean.csv`
            - `promotionsclean.csv`
            - `transfersclean.csv`
    - `.gitignore`
    - `LICENSE`
    - `README.md`

## Technologies Used.

- Google Colabs
    - Python
        - Pandas, Matplotlib, among other libraries
        - Used to read and process raw data, integrated into related data frames, and saved the consolidated data for further use.
        - Did some data exploration to find possible trends and insights useful to understand the dataset and create more advanced visualizations in a dashboard.
- Tableau Online
    - Made visualizations and an interactive dashboard showing analysis of processed data

## Project Approach.

*Split into the following 4 phases*…

### Phase 1: Project Charter

*Set the research goal and define the What? Why? and How?’s of the project.*

- **Research Goal**
    
    The objective of this project is to design and implement a data engineering solution that integrates and creates valuable insights from disparate data sources. These data insights will support Venmito’s business decisions and have an organized platform to gather their data.
    
- **Project Mission and Context**
    
    Venmito is a payment company that facilitates fund transfers between users and enables payments at participating stores. The company has a variety of data files in different formats. The goal is to clean and integrate this data to extract meaningful insights and provide structured methods for consuming the information for both technical and less technically inclined clients.
    
- **Analysis Approach**
    1. First using Google Colabs use features in Python and its libraries to create insights and visualizations that will give me an idea and direction of how I will add value to Venimto.
    2. Then use Tableau to create a dashboard and more elaborate visualizations and enrich the analysis.
- **Resources**
    1. Raw Data Files *(already provided).*
    2. Technologies Used *(mentioned previously).*
- **Deliverables**
    - Data Consumption Methods:
        - Technical Team:
            - Jupyter Notebook *(Source Code)*
        - Non-Technical Team:
            - Tableau Dashboard *(File and Video)*
    - README Documentation
- **Timeline**
    
    Friday, Feb. 21 *~delayed*
    
    - Phase 1. Define goal and plan.
    
    Saturday, Feb. 22
    
    - Phase 2. Data Preparation.
    - Phase 3. Data Exploration.
    
    Sunday, Feb. 23
    
    - Phase 3. *~continued.*
    - Phase 4. Presentation.
    
    Monday, Feb. 24
    
    - Wrap-Up/README *~submission due 2pm (ast).*

### Phase 2: Data Preparation

*Match and conform the raw data provided, enriching it and making it persistent*

In the Google Colab file there is a section for Data Processing divided in subsections for raw files. Here the data was read into data frames and integrated in order to make more meaningful connections and insights across the data provided. It was cleaned and joined, making sure of removing Null values and duplicate entities. The Data was cleaned into the files listed in the Cleaned Data subsection. These files are saved within the /content directory and offer a persistent solution and format to organize the companies data efficiently in a common format, in this case a .csv file.

### Phase 3: Data Exploration

In the Google Colab file there is a section for Data Exploration and Visualizations. The section is further divided by the data frames and insights being made. These include all sorts of visuals, such as heat maps, histograms, and bar charts, with listed key insights per block explaining what value is extracted from these visualizations.

### Phase 4: Presentation

The data and finding are presented in an interactive dashboard. This dashboard is divided in three main sections:

- A transactions key statistics summary
- An interactive section to gain insights on transactions, specifically on the following:
    - Which are the best cities, stores, items, and promotions
- A section to explore customer activity by:
    - Location, devices, activity over time, and customer retention

## Thank You.

*If you have any questions feel free to contact me at [ignaciosadurni@gmail.com](mailto:ignaciosadurni@gmail.com) …*
