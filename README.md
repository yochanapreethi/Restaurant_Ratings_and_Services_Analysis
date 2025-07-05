### Level 1 Tasks
1. **Data Exploration and Preprocessing**  
   - Examined dataset structure and missing values  
   - Handled missing data and performed necessary data type conversions  
   - Analyzed the distribution of the target variable, *Aggregate rating*

2. **Descriptive Analysis**  
   - Calculated statistical measures for numerical data  
   - Explored distributions of categorical variables such as *Country Code*, *City*, and *Cuisines*  
   - Identified top cuisines and cities with the highest number of restaurants

3. **Geospatial Analysis**  
   - Visualized restaurant locations using latitude and longitude  
   - Analyzed geographic distribution across cities and countries  
   - Explored correlations between location and ratings

4. **Online Delivery Analysis**  
   - Calculated the percentage of restaurants offering online delivery  
   - Compared average ratings of restaurants with and without online delivery

### Level 2 Tasks
1. **Table Booking and Online Delivery**  
   - Analyzed the availability and impact of table booking and online delivery on ratings and price ranges

2. **Price Range Analysis**  
   - Determined the most common price ranges and their corresponding average ratings  
   - Identified color coding associated with price ranges and ratings

3. **Feature Engineering**  
   - Created new features such as encoded indicators for table booking and online delivery  
   - Extracted additional features like name length for better predictive modeling

4. **Restaurant Chains Analysis**  
   - Identified restaurant chains by grouping on restaurant names  
   - Analyzed ratings, popularity (votes), and outlet counts of restaurant chains  
   - Visualized top chains by popularity

## Repository Structure

```
cognifyz/
│
├── restaurant.csv          # Dataset containing restaurant data
├── level1.ipynb            # Jupyter notebook for Level 1 tasks
└── level2.ipynb            # Jupyter notebook for Level 2 tasks
```

## Technologies Used

- Python  
- Pandas (Data Manipulation)  
- Matplotlib & Seaborn (Data Visualization)  
- Jupyter Notebook (Interactive Analysis)
