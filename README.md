# task_2

Data Cleaning: 

Imported necessary libraries: pandas, numpy, matplotlib.pyplot, and seaborn.

Loaded the dataset from Mobiles_Dataset.csv.

Checked for missing values.

Checked for duplicated rows and counted them.

Removed duplicate entries based on the Product Name column.

Cleaned the Rating column and Removed the string " Ratings"

Renamed the Reviews column to Overall_Reviews.

Cleaned the Overall_Reviews column and Removed the word "Reviews" and Removed commas.

Cleaned the Actual price and Discount price columns and Removed "₹" symbol and commas.

Converted to numeric (with coercion of errors).

Filled any missing values with 0.0.

Converted the values to integers.

Dashboard Insights
1.Total Mobile Models Count.
Number of unique mobile models in the dataset.

2. Brand Filter

Allows filtering analysis by specific brands (e.g., Apple, CMF, Google).

3. Most Reviewed Phone Brands

Total number of reviews per brand to identify popularity and customer engagement.

4. Top 5 Most Rated Phones

Devices with the highest average star ratings.

5. RAM and Storage Breakdown

Distribution of RAM sizes and internal storage across devices.

6. Total Sales by Brand

Total discount price sum by brand, indicating relative sales volume.

7. Performance Rating Scale

Comparison of brands based on their performance ratings (possibly average stars or derived scores).
