# EL_Task_2

Sample Superstore Power BI Dashboard

1. Imported the Data
I started by launching Power BI Desktop and imported the Sample Superstore dataset from an Excel file. I loaded the dataset into the Power BI model for further analysis.

2. Cleaned and Transformed the Data
Using Power Query Editor, I cleaned the dataset by:

Removing any null or unnecessary values,

Renaming columns for better clarity,

Changing data types appropriately,

Creating calculated columns where needed.

3. Created the Data Model
I ensured the data model was properly structured. Since I used a single dataset, relationships were straightforward. I then created DAX measures such as:

DAX
Copy
Edit
Sum of Sales = SUM(Sales[Sales])
Sum of Profit = SUM(Sales[Profit])
Sum of Quantity = SUM(Sales[Quantity])
4. Designed the Dashboard Layout
To create an intuitive layout, I:

Added a title text box at the top,

Inserted KPI cards to display Total Sales, Total Profit, and Quantity,

Added a slicer for filtering data by State.

5. Added Visualizations
I added multiple visuals to gain meaningful insights:

A line chart to show the trend of profit over time (by Order Date),

A bar chart showing profit breakdown by Sub-Category,

A table displaying sub-category-wise values (South vs. Total),

Donut charts for Profit by Region, Segment, and Category.

6. Formatted the Dashboard
I applied a dark theme for a professional look. I customized colors, added data labels, adjusted the layout, and aligned visuals to maintain a clean and engaging presentation.

7. Tested Interactivity
I interacted with the slicers and visuals to ensure the dashboard responded correctly to user input. This included filtering by state and checking tooltip accuracy.

8. Saved the Report
Finally, I saved the completed dashboard as a .pbix file.
