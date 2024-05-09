# Ownership of San Francisco's Newly Planted Trees

**Link**: https://ep393.github.io/info4310-hw1/

## Introduction
This visualization project focuses on the municipal trees of San Francisco, exploring the growth, species diversity, and the dynamic of tree ownership and maintenance. The project aims to highlight the collaborative efforts between the public and private sectors in enhancing the city’s green infrastructure.

## Story
The narrative of this visualization unfolds around the evolving dynamics of tree ownership and maintenance on San Francisco's city sidewalks. It emphasizes the crucial roles that both public and private sectors play in fostering and enhancing San Francisco's urban forest.

## Data Processing
### Dataset Used:
- **Street_Tree_List-2022-01-30_RAW.csv**

### Generated Datasets:
- **annual_summary.csv**: Focuses on the distribution and ownership of newly planted trees up to the year 2021. Trees without a "PlantDate" or not marked under "qCaretaker" as either "Private" or "DPW" were excluded.
- **caretaker_and_species.csv**: Focuses on the species distribution under different caretakers. Only entries with specified species and under the care of "Private" or "DPW" were included.

### Methods:
- Transformation of "PlantDate" into datetime format to isolate the year.
- Aggregation functions to count trees based on ownership.
- Extraction and cleaning of species names from "qSpecies".

## Design Rationale
### Visualizations:
- **Stacked Bar Chart**: Shows the number of trees planted each year from 1969 to 2022, categorized by ownership (DPW in blue, private in green). This chart illustrates annual greening efforts and the joint contributions of public and private entities.
- **Pie Chart**: Provides a breakdown of tree species within the urban forest, color-coded to differentiate species and caretakers, highlighting the biodiversity of the city’s green spaces.

## Visual Encodings
### Stacked Bar Chart:
- Utilizes position, length, and color to convey the data.
- X-axis represents the year, and Y-axis quantifies the number of trees planted each year.
- Colors distinguish between DPW and private ownership.

### Pie Chart:
- Utilizes angle, color, and area to represent the distribution of the top five tree species under DPW and private ownership.
- Distinct colors enhance readability and facilitate species comparison.

## Conclusion
This project not only provides a visual representation of tree planting trends and species diversity but also underscores the importance of partnership in urban environmental management. Through effective visual encodings, the complex data about San Francisco’s urban forest is made accessible and engaging.
