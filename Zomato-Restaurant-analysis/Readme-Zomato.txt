#### **Zomato Restaurant Data Analysis**

**Project Overview**
This project performs an Exploratory Data Analysis (EDA) on Zomato restaurant data using Python to extract insights regarding pricing structures, customer ratings, online ordering behavior, booking availability, and cuisine popularity.

**Tools and Libraries Used**
* **Python** (Core Processing)
* **Pandas** (Data Cleaning and Manipulation)
* **NumPy** (Numerical operations)
* **Matplotlib** (Data Visualization foundations)
* **Seaborn** (Advanced styling & statistical data charts)

**Dataset Attributes**
The analysis primarily utilizes the following features from the dataset:
* `cuisines type`: Core and secondary cuisine variations offered by each restaurant.
* `restaurant type`: Categorized tags representing the format of the venue (e.g., Cafe, Fine Dining, Quick Bites).
* `average cost for two people`: The structural price bracket for dining.
* `customer rating`: Calculated numerical user reviews.
* `online order`: Availability of digital food delivery ordering.
* `table booking`: System permissions for reserving tables ahead of time.

**Key Insights**
* **Cuisine Dominance:** **North Indian** cuisine strongly dominates the dataset as the most frequently served offering, followed closely by **Chinese** and **South Indian** options.
* **Premium Features:** Table booking availability is rare (only **10.5%** of restaurants offer it) and is heavily tied to premium tiers; expensive venues (above 1,500) consistently offer it, correlating heavily with stronger, consolidated customer ratings.
* **Online Ordering:** Establishments that accept online orders present fewer extremely low-rated outliers and yield a slightly higher overall median customer rating compared to offline-only restaurants.
* **Cost Correlation:** Standalone premium restaurant brackets such as **"Fine Dining, Lounge"** and **"Fine Dining, Microbrewery"** top the financial charts, averaging costs up to **3,000** for two people.

**Project Files**
* `zomato.ipynb` → The primary Jupyter Notebook containing code cells, visualizations, and annotations.
* `zomato.csv` → The underlying clean structured source dataset.

**How to Run**
1. Download or clone this repository repository folder.
2. Open the project inside Jupyter Notebook or an active VS Code environment.
3. Ensure the `zomato.csv` file is placed in the same relative working directory.
4. Execute the cells sequentially to reproduce the visualizations and insights.

**Author**
Rohit Manjrekar