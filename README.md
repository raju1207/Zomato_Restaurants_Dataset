# Zomato_Restaurants_Dataset

This repository contains a dataset of restaurants from Zomato, including information on their ratings, costs, services, and more. The data is useful for analyzing restaurant trends, customer preferences, and service availability.

## Dataset Overview

- **Number of Records**: 7,105
- **Number of Columns**: 12

### Column Descriptions

1. **Unnamed: 0.1 & Unnamed: 0**: Index columns that may be redundant.
2. **restaurant name**: Name of the restaurant.
3. **restaurant type**: Category/type of the restaurant (e.g., Quick Bites, Cafe).
4. **rate (out of 5)**: Average rating of the restaurant.
5. **num of ratings**: Number of user ratings.
6. **avg cost (two people)**: Average cost for two people.
7. **online_order**: Availability of online order service (Yes/No).
8. **table booking**: Availability of table booking service (Yes/No).
9. **cuisines type**: Types of cuisines served.
10. **area**: Area where the restaurant is located.
11. **local address**: Detailed local address of the restaurant.

## Usage

This dataset can be used for various purposes, such as:
- Restaurant trend analysis
- Price comparison and prediction models
- Service availability mapping

## How to Use

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Load the dataset into your Python environment using pandas:
   ```python
   import pandas as pd
   data = pd.read_csv('zomato.csv')
   ```

## License

This dataset is provided for educational and analytical purposes.

