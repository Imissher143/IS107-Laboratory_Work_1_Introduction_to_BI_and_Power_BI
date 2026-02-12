# IS107 - Laboratory Work 1 | Introduction to BI and Power BI

---

## PART 1: Launching Power BI & Loading Data 

### Step 1: Open Power BI Desktop 
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d6cd68d5-46d2-4175-a705-2ea5bb8e5842" />

### Step 2: Load the Dataset 
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/92121e74-8ea9-4b5c-815c-fc63024e1223" />

### Step 3: Verify Data in Data View 
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/f11fea86-0059-4e63-863a-79e7475fca84" />

---

## PART 2: Exploring the Interface 

### Report View
<img width="1918" height="1079" alt="image" src="https://github.com/user-attachments/assets/10de805e-677a-48ba-beeb-31907ee879dd" />

### Data View
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/0be169a2-9de4-483f-bc0d-ba7e033f8b00" />

### Model View
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/18ba7ec9-3da3-4f41-b861-cf71e49822d5" />

---

## PART 3: Creating Auto-Generated Visuals 

### Step 1: Quick Visualization 
<img width="390" height="286" alt="image" src="https://github.com/user-attachments/assets/c32895f3-4f65-4f45-a8b9-c044ada52f47" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>What type of chart was created?</strong> It creates a single vertical bar chart.</li>
  <li><strong>What does it show?</strong> A value of around 250,000 as the sum of sales.</li>
</ul>

### Step 2: Create a Sales by Region Chart 
<img width="395" height="282" alt="image" src="https://github.com/user-attachments/assets/d90cdaba-315d-40f5-a3b8-f2969e50c808" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>Which region has the highest sales?</strong> The West Region has the highest sales.</li>
</ul>

### Step 3: Sales by Category 
<img width="394" height="282" alt="image" src="https://github.com/user-attachments/assets/07105d61-2a8d-4bbd-ac75-2c4fe8584114" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>Which category dominates?</strong> The Electronics Category dominates with the largest sales.</li>
  <li><strong>Is the distribution balanced?</strong> No, the distribution is not balanced because Office Supplies have a much smaller share compared to Electronics and Furniture.</li>
</ul>

### Step 4: Sales Over Time 
<img width="392" height="283" alt="image" src="https://github.com/user-attachments/assets/e83206e9-b30c-47a4-a6b6-692772c3a43e" />

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
<img width="363" height="286" alt="image" src="https://github.com/user-attachments/assets/b9060830-54e9-49a3-bb57-bd0c32cc2819" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>What is the total sales amount?</strong> The Total sales amount to 220K(Two Hundred and Twenty Thousand.)</li>
</ul>

### Task 2: Add Slicer 
<img width="365" height="284" alt="image" src="https://github.com/user-attachments/assets/91ebbab0-6da9-4a1a-b3d1-23c00912c249" />

<span style="font-size:25px; font-weight:bold;">Question:</span>
<ul>
  <li><strong>What happens to other visuals when you click a region?</strong> All other visuals update to show data only for the selected region, helping focus on regional performance.</li>
  <li><strong>Why is filtering important in BI?</strong> Filtering allows you to analyze specific data subsets, making insights faster and more accurate.</li>
</ul>

### Task 3: Sort Sales 
<img width="589" height="296" alt="image" src="https://github.com/user-attachments/assets/40ba06d1-4bd8-461f-b47b-3b1517276d1f" />

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

