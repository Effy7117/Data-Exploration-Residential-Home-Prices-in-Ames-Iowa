# Data Exploration: Residential Home Prices in Ames, Iowa

### Business Objective

PCLE Constructors, a consortium of independent construction firms operating across Canada, the United States, the Caribbean, and Australia, is embarking on a new project. Their objective is to construct a residential apartment comprising 50 units in Ames, Iowa. This endeavor has the purpose to provide affordable yet profitable housing solutions to potential buyers. The cornerstone of this project is the accurate prediction of the final sale price of residential homes in Ames, Iowa, enabling PCL Constructors to align their pricing strategies with market dynamics.
### Dataset Descritption

The dataset is obtained from the "House Prices - Advanced Regression Techniques" competition.
- Location: Kaggle competition page.
- Data Reference: Anna Montoya, DataCanary. (2016). House Prices - Advanced Regression Techniques. Kaggle.
https://kaggle.com/competitions/house-prices-advanced-regression-techniques

### Data collection process
- Kaggle competitions often provide datasets for participants to download directly from the competition page. This typically involves clicking on a "Download" button or accessing a provided link.

- Issues Encountered: 
  - Kaggle datasets are generally well-prepared, but potential issues might include missing values, inconsistent formatting, or outliers.
  - In some cases, data preprocessing challenges may arise, such as dealing with categorical variables, handling missing data, or normalizing numerical features.

- Resolutions:
  - Cleaning and preprocessing: Participants typically perform data cleaning and preprocessing steps to address missing values, outliers, and other issues. This may involve techniques such as imputation, outlier removal, or data normalization.
  - Feature engineering: Participants might create new features or transform existing ones to improve model performance.
  - Exploratory Data Analysis (EDA): Understanding the data through EDA can help identify patterns and inform preprocessing decisions.

### Data Descripition
**File descriptions:**
* train.csv - the training set
* quality_score - gives additional details of quality of location 

**Format of the Data:**

* The data is organized as a tabular dataset, in CSV (Comma-Separated Values) format.
* Each row represents a unique observation or record, while each column represents a different variable or feature.

**Quantity of Data in train.csv:**

* Total Records (Rows): 1460
* Total Fields (Columns): 80

**Column Names and Descriptions in train.csv:**
* **SalePrice**: the property's sale price in dollars. This is the target variable that you're trying to predict.
* **MSSubClass**: The building class
* **MSZoning**: The general zoning classification
* **LotFrontage**: Linear feet of street connected to property
* **LotArea**: Lot size in square feet
* **Street**: Type of road access
* **Alley**: Type of alley access
* **LotShape**: General shape of property
* **LandContour**: Flatness of the property
* **Utilities**: Type of utilities available
* **LotConfig**: Lot configuration
* **LandSlope**: Slope of property
* **Neighborhood**: Physical locations within Ames city limits
* **Condition1**: Proximity to main road or railroad
* **Condition2**: Proximity to main road or railroad (if a second is present)
* **BldgType**: Type of dwelling
* **HouseStyle**: Style of dwelling
* **OverallQual**: Overall material and finish quality
* **OverallCond**: Overall condition rating
* **YearBuilt**: Original construction date
* **YearRemodAdd**: Remodel date
* **RoofStyle**: Type of roof
* **RoofMatl**: Roof material
* **Exterior1st**: Exterior covering on house
* **Exterior2nd**: Exterior covering on house (if more than one material)
* **MasVnrType**: Masonry veneer type
* **MasVnrArea**: Masonry veneer area in square feet
* **ExterQual**: Exterior material quality
* **ExterCond**: Present condition of the material on the exterior
* **Foundation**: Type of foundation
* **BsmtQual**: Height of the basement
* **BsmtCond**: General condition of the basement
* **BsmtExposure**: Walkout or garden level basement walls
* **BsmtFinType1**: Quality of basement finished area
* **BsmtFinSF1**: Type 1 finished square feet
* **BsmtFinType2**: Quality of second finished area (if present)
* **BsmtFinSF2**: Type 2 finished square feet
* **BsmtUnfSF**: Unfinished square feet of basement area
* **TotalBsmtSF**: Total square feet of basement area
* **Heating**: Type of heating
* **HeatingQC**: Heating quality and condition
* **CentralAir**: Central air conditioning
* **Electrical**: Electrical system
* **1stFlrSF**: First Floor square feet
* **2ndFlrSF**: Second floor square feet
* **LowQualFinSF**: Low quality finished square feet (all floors)
* **GrLivArea**: Above grade (ground) living area square feet
* **BsmtFullBath**: Basement full bathrooms
* **BsmtHalfBath**: Basement half bathrooms
* **FullBath**: Full bathrooms above grade
* **HalfBath**: Half baths above grade
* **Bedroom**: Number of bedrooms above basement level
* **Kitchen**: Number of kitchens
* **KitchenQual**: Kitchen quality
* **TotRmsAbvGrd**: Total rooms above grade (does not include bathrooms)
* **Functional**: Home functionality rating
* **Fireplaces**: Number of fireplaces
* **FireplaceQu**: Fireplace quality
* **GarageType**: Garage location
* **GarageYrBlt**: Year garage was built
* **GarageFinish**: Interior finish of the garage
* **GarageCars**: Size of garage in car capacity
* **GarageArea**: Size of garage in square feet
* **GarageQual**: Garage quality
* **GarageCond**: Garage condition
* **PavedDrive**: Paved driveway
* **WoodDeckSF**: Wood deck area in square feet
* **OpenPorchSF**: Open porch area in square feet
* **EnclosedPorch**: Enclosed porch area in square feet
* **3SsnPorch**: Three season porch area in square feet
* **ScreenPorch**: Screen porch area in square feet
* **PoolArea**: Pool area in square feet
* **PoolQC**: Pool quality
* **Fence**: Fence quality
* **MiscFeature**: Miscellaneous feature not covered in other categories
* **MiscVal**: Value of miscellaneous feature
* **MoSold**: Month Sold
* **YrSold**: Year Sold
* **SaleType**: Type of sale
* **SaleCondition**: Condition of sale

**Quantity of Data in quality_score.csv:**

* Total Records (Rows): 1460
* Total Fields (Columns): 3

**Column Names and Descriptions in quality_score.csv:**
* **Id**: Id of each data
* **LocationQualityScore**: Overall quality of the location in 10.
* **LivingAreaQuality**: Represent a score reflecting the quality of the living area in 100


**Surface Features Discovered:**
* The dataset covers a diverse set of features related to residential properties, including physical characteristics, construction details, and amenities.
* Some features contain missing values that may need to be addressed during data preprocessing.
* Temporal information, such as construction and remodel dates, is included.
* There are various quality and condition ratings for different aspects of the properties, including material quality, basement condition, and garage condition.
* The dataset provides a comprehensive foundation for predicting property sale prices based on a variety of factors.
* Understanding these features and their relationships will be crucial for effective data analysis, preprocessing, and model building in the context of predicting house prices.
