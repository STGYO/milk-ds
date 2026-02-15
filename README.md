# Milk Dataset Collection (milk-ds)

A comprehensive collection of milk production, consumption, and sales datasets from India, compiled from government sources and industry data.

## Overview

This repository contains datasets related to the dairy industry in India, including:
- Milk production statistics by state and animal type
- Per capita milk availability and consumption patterns
- Milk pricing and procurement data
- Dairy product sales information

## Repository Structure

```
milk-ds/
├── GOV MILK DATA/           # Government datasets from data.gov.in
│   ├── All India level Milk Procurement by Dairy Cooperatives/
│   ├── State-wise Details of Average Consumer Sale Price of Toned Milk/
│   ├── StateUT-wise Estimates of Milk Production/
│   ├── Year-wise Capita availability of Milk/
│   └── Details of estimates of milk production/
└── KAGGLE MILK DATA/        # Commercial dairy sales dataset
    └── dairy_dataset.csv
```

## Datasets

### 1. Government of India Data (GOV MILK DATA)

#### 1.1 All India Level Milk Procurement (2014-15 to 2018-19)
- **File**: `RS_249_AU3064.csv`
- **Source**: Ministry of Fisheries, Animal Husbandry and Dairying
- **Description**: Annual milk procurement data by dairy cooperatives across India
- **Period**: 2014-15 to 2018-19
- **Metrics**: Procurement in TKgPD (Thousand Kilograms Per Day)

#### 1.2 State-wise Average Consumer Sale Price of Toned Milk (2024-25)
- **File**: `RS_Session_267_AU_3586_A.csv`
- **Description**: Average consumer sale price of toned milk across different states and milk unions
- **Period**: April 2024 to February 2025
- **Metrics**: Price in rupees per liter

#### 1.3 StateUT-wise Milk Production by Animal Type

##### Buffalo (2007-08 to 2011-12)
- **File**: `Milk_Buffalo_07_12_n.csv`
- **Description**: State/UT-wise estimates of milk production from buffaloes
- **Metrics**: Number of animals in milk, average yield per animal, total milk production

##### Cows (2007-08 to 2011-12)
- **File**: `Est_Milk_NDB_07_12.csv`
- **Description**: State/UT-wise estimates of milk production from non-descript/indigenous cows
- **Metrics**: Number of animals in milk, average yield per animal, total milk production

##### Goats (2007-08 to 2011-12)
- **File**: `datafile.csv`
- **Description**: State/UT-wise estimates of milk production from goats
- **Metrics**: Number of animals in milk, average yield per animal, total milk production

#### 1.4 State/UT-wise Milk Production (2013-14 to 2016-17)
- **File**: `RJ_Session_246_AU2753_1.csv`
- **Source**: Ministry of Agriculture and Farmers Welfare
- **Description**: Total milk production by state/UT
- **Period**: 2013-14 to 2016-17
- **Metrics**: Production in thousand tonnes

#### 1.5 Year-wise Per Capita Availability of Milk (2017-18 to 2019-20)
- **File**: `RS_Session_255_AU_2340_A.csv`
- **Description**: National per capita availability of milk
- **Period**: 2017-18 to 2019-20
- **Metrics**: Per capita availability in grams per day

#### 1.6 Detailed Animal-wise Production Estimates (2008-09 to 2012-13)

##### Buffaloes
- **File**: `Animal_Husbandry_TABLE10_2012-13.csv`
- **Description**: Detailed estimates of milk production from buffaloes by state

##### Non-descript Indigenous Cows
- **File**: `Animal_Husbandry_TABLE9_2012-13.csv`
- **Description**: Detailed estimates of milk production from indigenous cows by state

##### Goats
- **File**: `Animal_Husbandry_TABLE11_2012-13.csv`
- **Description**: Detailed estimates of milk production from goats by state

### 2. Kaggle Dairy Goods Sales Dataset

#### Dairy Dataset (Commercial Sales Data)
- **File**: `dairy_dataset.csv`
- **Description**: Comprehensive commercial dairy product sales dataset including production, inventory, and sales information
- **Columns**:
  - Location details (farm location, land area, number of cows, farm size)
  - Product information (Product ID, Name, Brand)
  - Pricing and sales (quantity, price per unit, total revenue)
  - Storage and logistics (shelf life, storage conditions, production/expiration dates)
  - Inventory management (stock levels, reorder thresholds)
  - Sales channels (customer location, sales channel)
- **Products**: Includes various dairy products like milk, ice cream, cheese, yogurt, etc.

## Data Sources

All datasets in this repository are sourced from the following official sources:

1. **State/UT-wise Estimates of Milk Production by Animal**  
   https://www.data.gov.in/catalog/stateut-wise-estimates-milk-production-animal

2. **Kaggle Dairy Goods Sales Dataset**  
   https://www.kaggle.com/datasets/suraj520/dairy-goods-sales-dataset

3. **State-wise Details of Average Consumer Sale Price of Toned Milk (2024-25)**  
   https://www.data.gov.in/resource/state-wise-details-average-consumer-sale-price-toned-milk-country-during-2024-25

4. **Year-wise Per Capita Availability of Milk (2017-18 to 2019-20)**  
   https://www.data.gov.in/resource/year-wise-capita-availability-milk-country-2017-18-2019-20

5. **All India Level Milk Procurement by Dairy Cooperatives (2014-15 to 2018-19)**  
   https://www.data.gov.in/resource/all-india-level-milk-procurement-dairy-cooperatives-2014-15-2018-19-ministry-fisheries

6. **State/UT-wise Milk Production (2013-14 to 2016-17)**  
   https://www.data.gov.in/resource/stateut-wise-milk-production-2013-14-2016-17-ministry-agriculture-and-farmers-welfare

## Usage

These datasets can be used for:
- Statistical analysis of milk production trends across India
- Research on dairy industry patterns and regional variations
- Machine learning models for demand forecasting
- Price analysis and market studies
- Supply chain optimization
- Regional dairy farming insights

## Data Format

Most government datasets are in CSV format with the following typical structure:
- State/UT-wise breakdowns
- Time series data (yearly/quarterly)
- Multiple metrics (production volume, prices, animal counts, yields)

The Kaggle dataset is a single CSV file with comprehensive columns covering the entire dairy supply chain from production to sales.

## License

This repository is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

Note: Individual datasets may have their own licensing terms as specified by their original sources (data.gov.in and Kaggle).

## Contributing

Contributions to expand or update this dataset collection are welcome. Please ensure that any new datasets include proper attribution and follow the licensing requirements of the original sources.

## Acknowledgments

- Government of India Open Data Platform (data.gov.in)
- Ministry of Fisheries, Animal Husbandry and Dairying
- Ministry of Agriculture and Farmers Welfare
- Kaggle community and dataset contributors
