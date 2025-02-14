**Data Cleaning Steps**

1. **Merged all three datasets** from different time periods using **Tableau Prep Builder**.  
     1. [Superstore Sales(2011-2014)](data/Superstore_Sales(2011-2014))
     2. [Superstore Sales(2015-2018)](data/Sample_Superstore(2015-2019))
     3. [Superstore Sales(2019-2022)](data/cleaned_superstore_dataset(2019-2022))
      
3. **Removed redundant and unnecessary columns** to improve data quality.
4. Made sure there are no ** missing values** 
5. **Standardized categorical values** to avoid duplication (e.g., “NY” vs. “New York”).
6. **Created a final cleaned dataset [Cleaned Data(2011-2022)](data/Cleaned_data/Superstore_Sales(2011-2022).csv)** ready for visualization.

7. ### 📜 **Data Preparation File**
You can find the **Tableau Prep workflow file (`Flow1.tflx`)** in the `Tableau_Prep/` folder. To reproduce the cleaned dataset:
1. Open **Tableau Prep Builder**.
2. Load the **`Flow1.tflx`** file.
3. Run the workflow to generate `Superstore Sales(2011-2022).csv`.
