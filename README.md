#  Real Estate Search

A Python-based **Real Estate Search System** that uses **Data Mining and data preprocessing techniques** to help users find properties based on their requirements such as location, budget, bedrooms, bathrooms, and house size.

The project works with real-estate listing data, cleans and processes the dataset, and provides a faster way to search and filter properties.

## Dataset link:- https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset

##  Overview

Finding suitable properties from a large real-estate dataset can be difficult because of the amount of available information.

This project applies **Data Mining techniques** to process real-estate data and provide relevant property listings based on user-defined criteria.

Users can specify requirements such as:

*  City
*  State
*  Budget / Price
*  Number of Bedrooms
*  Number of Bathrooms
*  House Size

The system then searches the processed dataset and returns properties matching the selected criteria.


## Objectives

The main objectives of this project are:

* Process and clean real-estate datasets.
* Handle missing and inconsistent data.
* Extract useful information from property listings.
* Allow users to search properties using multiple criteria.
* Improve search efficiency through optimized filtering.
* Apply Data Mining concepts to a real-world dataset.
* Provide relevant property recommendations based on user requirements.


## Technologies Used

| Technology       | Purpose                                 |
| ---------------- | --------------------------------------- |
| **Python**       | Core development                        |
| **Pandas**       | Data processing and analysis            |
| **NumPy**        | Numerical operations                    |
| **Scikit-learn** | Data preprocessing and machine learning |
| **CSV Dataset**  | Real-estate listing data                |
| **Git & GitHub** | Version control                         |



## Dataset

The project uses a real-estate dataset containing information about property listings.

Important attributes include:

brokered_by
status
price
bed
bath
acre_lot
street
city
state
zip_code
house_size
prev_sold_date


The dataset contains both numerical and categorical attributes that can be processed to support property search and analysis.


## Data Mining Pipeline

The project follows a data-processing pipeline:

              Real Estate Dataset
                       │
                       ▼
              Data Collection
                       │
                       ▼
              Data Cleaning
                       │
             ┌─────────┴─────────┐
             │                   │
             ▼                   ▼
       Missing Values      Invalid Data
             │                   │
             └─────────┬─────────┘
                       ▼
              Data Preprocessing
                       │
                       ▼
              Feature Selection
                       │
                       ▼
             Property Filtering
                       │
                       ▼
              Search Results



## Data Preprocessing

Real-world datasets often contain missing or inconsistent values.

The project performs preprocessing operations such as:

* Handling missing values
* Removing or processing invalid records
* Cleaning property information
* Selecting relevant features
* Preparing numerical features
* Encoding categorical features

The primary features used for property analysis include:

City
State
House Size
Bedrooms
Bathrooms
Price


## Property Search

The search system allows users to specify multiple requirements.

### Example

A user could search for:

City: Dehradun
State: Uttarakhand
Maximum Budget: ₹50,00,000
Bedrooms: 3
Bathrooms: 2

The system processes these requirements and filters the dataset to find matching properties.

### Search Flow

User Requirements
       │
       ▼
Input Validation
       │
       ▼
Apply Search Filters
       │
       ▼
Search Processed Dataset
       │
       ▼
Matching Properties
       │
       ▼
Display Results


## Search Optimization

To improve search performance, the project uses optimized filtering and caching techniques.

Instead of repeatedly processing the entire dataset for similar searches, previously processed information can be reused where applicable.

This helps make property searches faster and more efficient.


## Data Mining Concepts Used

This project demonstrates several practical Data Mining concepts:

* Data Cleaning
* Data Preprocessing
* Feature Selection
* Data Filtering
* Exploratory Data Analysis
* Categorical Data Processing
* Numerical Data Processing
* Pattern-based Search
* Dataset Optimization


## Project Structure

Real-Estate-Search/
│
├── data/
│   ├── realtor-data.zip.csv
│   ├── cleaned_realtor_data.csv
│   └── filled_dataset.csv
│
├── src/
│   ├── data_cleaning.py
│   ├── preprocessing.py
│   ├── search.py
│   └── main.py
│
├── requirements.txt
├── README.md
└── LICENSE

> Update the structure above if your actual repository uses different filenames or folders.



##  Installation

### 1. Clone the repository

```bash
git clone https://github.com/rohanchandrajwar/Real-Estate-Search.git
```

### 2. Navigate to the project

```bash
cd Real-Estate-Search
```

### 3. Install dependencies

```bash
pip install pandas numpy scikit-learn
```

Or, if a `requirements.txt` file is available:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the main Python program:

```bash
python main.py
```

Enter the desired property requirements when prompted.

For example:


Enter city: Dehradun
Enter state: Uttarakhand
Enter maximum budget: 5000000
Enter bedrooms: 3
Enter bathrooms: 2


The program returns properties matching the specified requirements.


##  Example Output

Property Search Results
--------------------------------

City: Dehradun
State: Uttarakhand
Price: ₹48,00,000
Bedrooms: 3
Bathrooms: 2
House Size: 1650 sq ft

--------------------------------

City: Dehradun
State: Uttarakhand
Price: ₹45,00,000
Bedrooms: 3
Bathrooms: 2
House Size: 1500 sq ft


##  Learning

Through this project, I gained practical experience with:

* Working with large real-world datasets
* Data cleaning and preprocessing
* Handling missing values
* Feature selection
* Data Mining techniques
* Pandas and NumPy
* Building search systems using structured data
* Optimizing dataset filtering
* Working with categorical and numerical data
* Applying programming concepts to a real-world problem



## 🔮 Future Improvements

Possible improvements include:

* [ ] Add a graphical user interface
* [ ] Add map-based property search
* [ ] Add property recommendation functionality
* [ ] Add price prediction using machine learning
* [ ] Add advanced sorting and ranking
* [ ] Add user accounts and saved searches
* [ ] Add more location-based filters
* [ ] Add visualization and analytics dashboards
* [ ] Deploy the application as a web application

