Link To PDF: https://drive.google.com/file/d/1Tth80cO1rLSYMuP0NEczf8rZf4g1yQlV/view?usp=drive_link

# IS107 - Laboratory Work 1 - Introduction to Business Intelligence & Power BI 

---

## PART 1: Launching Power BI & Loading Data 

### Step 1: Open Power BI Desktop
-  *This screenshot shows the Power BI Desktop startup screen after launching the application, ready for data import and analysis.*
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/7628ef61-1b6c-4e01-96e0-06c31bd01e07" />

### Step 2: Load the Dataset 
-  *This screenshot shows the process of importing the CSV dataset into Power BI Desktop, where the file `Week1_Basic_Sales_Data.csv` is selected and loaded for analysis.*
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/2b95415a-7f73-4222-a87d-609f69547be5" />

### Step 3: Verify Data in Data View
-  *This screenshot shows the dataset loaded in Power BI's Data View, where all columns are visible and data types for each column can be verified and adjusted if needed.*
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/7aeb9cdb-8c18-4f72-9fd4-a572f3a260a5" />

---

## PART 2: Exploring the Interface 

### Report View
-  *This screenshot shows Power BI's Report View, where users can create and arrange visuals like charts and graphs on the canvas.*
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/9ddfb996-638d-4b59-b4ed-047b90858b93" />

### Data View
-  *This screenshot shows Power BI's Data View, which allows users to see and inspect the raw dataset, including all rows and columns.*
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/cf70805b-f8b9-4b54-9c3a-8e405ccb7b9d" />

### Model View
-  *This screenshot shows Power BI's Model View, where relationships between tables can be created and managed for proper data modeling.*
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/b0598da5-1546-435e-9c07-42c7fcd72747" />

---

## PART 3: Creating Auto-Generated Visuals 

### Step 1: Quick Visualization 
-  *This screenshot shows the automatic chart created when the Sales field is dragged onto the canvas, giving a quick summary of total sales.*
<img width="382" height="273" alt="image" src="https://github.com/user-attachments/assets/0c240d3a-0d7d-4f5f-9952-ae800e14f4fd" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>What type of chart was created?</strong> It creates a single vertical bar chart.</li>
  <li><strong>What does it show?</strong> A value of around 250,000 as the sum of sales.</li>
</ul>

Question:

Are all columns visible?
Is “Date” formatted as Date?
Is “Sales” formatted as Decimal Number?
Answers:

Yes, all columns are visible in the Data View.
Yes, all data in date are formated as date
No, the sales is not formatted as decimal, it was formatted as whole number

### Step 2: Create a Sales by Region Chart 
-  *This screenshot shows a Clustered Column Chart displaying total sales per region, helping to compare regional performance visually.*
<img width="383" height="270" alt="image" src="https://github.com/user-attachments/assets/f9c239b6-cd50-406a-8dab-4d256d9a3b54" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>Which region has the highest sales?</strong> The West Region has the highest sales.</li>
</ul>

### Step 3: Sales by Category 
-  *This screenshot shows a Pie Chart representing sales distribution across different product categories, highlighting the dominant categories.*
<img width="381" height="267" alt="image" src="https://github.com/user-attachments/assets/363029d2-e34f-4f57-b873-f6686c6e5060" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>Which category dominates?</strong> The Electronics Category dominates with the largest sales.</li>
  <li><strong>Is the distribution balanced?</strong> No, the distribution is not balanced because Office Supplies have a much smaller share compared to Electronics and Furniture.</li>
</ul>

### Step 4: Sales Over Time 
-  *This screenshot shows a Line Chart illustrating the trend of sales over time, making it easy to identify growth or decline patterns.*
<img width="382" height="267" alt="image" src="https://github.com/user-attachments/assets/56e08de9-9593-4f52-b91b-9ba620fc6941" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>Is there growth?</strong> No, there is no growth, sales have decreased from 2024 to 2025.</li>
  <li><strong>Any noticeable trend?</strong> Yes, there is a clear downward trend showing a significant decline in Sales.</li>
</ul>

---

### PART 4: Basic Data Insight Interpretation 

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>Which region contributes the most revenue?</strong> The Region contributes the most revenue.</li>
  <li><strong>Which product category performs best?</strong> Electronic products.</li>
  <li><strong>Are sales consistent across dates?</strong> No, the Sales are not consistent as it goes down significantly from 2024 to 2025.</li>
  <li><strong>What business recommendation can you suggest?</strong> Investigate why the drop in sales, boost high performance Products, and improve lower performance regions.</li>
</ul>

---

## LABORATORY QUESTIONS 

### Part A – Technical Questions

1. **What are the five columns in the dataset?**  
   -  Date, Product, Category, Region, and Sales are the five columns in the dataset.

2. **What data type is assigned to the “Sales” column?**  
   -  Decimal Number

3. **Which Power BI view allows you to see raw data?**  
   -  Table Data, as it allows us to see raw data in Power BI.

4. **What chart type is best for showing trends over time?**  
   -  Line Chart, because it clearly displays changes in values overtime.

5. **What aggregation is automatically applied to Sales?**  
   -  By default, Power BI applies the Sum aggregation to numeric fields like Sales.

### Part B – Analytical Questions

6. **Which region has the highest total sales?**  
   -  The West Region has the highest Total Sales with 55,851 total sum of sales.

7. **Which category has the lowest performance?**  
   -  Office Supplies has the lowest performing category, accounting for only 19.99%(44K) of Total sales.

8. **Are sales increasing, decreasing, or stable?**  
   -  Sales are significantly decreasing as it shows adownward trend from 2024 to 2025.

9. **If you were a manager, which region would you prioritize?**  
   -  I’ll Prioritize the North region for intervention, as it is the only territory significantly underperforming compared to the others.
     
10. **Provide one actionable recommendation based on the data.**  
    -  To investigate the year over year crash, perform a root cause analysis to determine if the steep sales decline stems from market shifts, internal operational failures, or incomplete 2025 reporting.

---

## ENHANCEMENT SECTION - Advanced Exploration 

### Task 1: Add a Card Visualization 
-  *This screenshot shows a Card visualization displaying the total sales amount.*
<img width="352" height="269" alt="image" src="https://github.com/user-attachments/assets/67000b94-f0e5-406a-9d62-b5de20796097" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>What is the total sales amount?</strong> The Total sales amount to 220K(Two Hundred and Twenty Thousand.)</li>
</ul>

### Task 2: Add Slicer 
-  *This screenshot shows a Slicer added for the Region field, allowing users to filter all visuals on the report page based on the selected region.*
<img width="354" height="272" alt="image" src="https://github.com/user-attachments/assets/338e5c16-3fe1-4807-8e6c-8a965352e634" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>What happens to other visuals when you click a region?</strong> All other visuals update to show data only for the selected region, helping focus on regional performance.</li>
  <li><strong>Why is filtering important in BI?</strong> Filtering allows you to analyze specific data subsets, making insights faster and more accurate.</li>
</ul>

### Task 3: Sort Sales 
-  *This screenshot shows the Region chart sorted by sales in descending order, making it easier to see the highest and lowest performing regions.*
<img width="593" height="293" alt="image" src="https://github.com/user-attachments/assets/e93444a6-fb99-49d2-ae98-483cbacda7f1" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>Does sorting improve readability?</strong>  Yes, sorting makes it easier to compare values at a glance.</li>
  <li><strong>Why?</strong> It organizes the data from highest to lowest (or vice versa), allowing users to quickly identify top and bottom performing regions.</li>
</ul>

### Task 4: Identify Outliers 

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>Which region is significantly higher or lower?</strong>  The North region is on the lower end. While the West, East, and South regions are all performing consistently near the 60K mark.</li>
  <li><strong>What might explain that difference?</strong> The North’s lower performance likely stems from a smaller customer base, stronger local rivals, or fewer company resources being assigned to that territory.</li>
</ul>

---

## Insight Summary

1. The West Region generates the highest revenue.
2. Electronics is the best-performing product category.
3. Sales show a clear downward trend from 2024 to 2025.
4. Office Supplies significantly underperforms compared to other categories.
5. The North Region requires strategic attention to improve sales performance.

