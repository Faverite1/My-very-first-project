# Bike Sales Purchase Analysis Report

## Introduction
This analysis report investigates bike buyers based on various demographic factors, including educational degrees, age brackets, and income levels in a specific region. The dataset was sourced from the Data Analytics/Science class by PSP Analytic.

## Data Analysis Process
The analysis followed these key steps:

1. **Data Collection**
2. **Data Cleaning and Formatting**
3. **Data Exploration**
4. **Data Visualization**
5. **Insights and Recommendations**

## Data Collection
The dataset was obtained from an email by Joseph Elijah, containing an assessment spreadsheet and group assessment questions. The spreadsheet was reviewed in Microsoft Excel, and multiple data columns and rows were analyzed based on the provided questions.

### Key Questions:
**A. Data Cleansing**
- Remove duplicates.
- Replace "M" and "S" in the marital status column with "Married" and "Single" respectively; "M" and "F" in the gender column with "Male" and "Female."
- Format the income column to display values with '0' decimal places.
- Create age brackets: "Adolescents" (0-30), "Middle Age" (31-54), and "Old" (55+).

**B. Data Analysis/Visualization**
- Use Pivot Tables and charts to analyze:
  - Average income by gender and bike purchase history.
  - Distance traveled by commuters and bike purchases.
  - Age bracket and bike purchases.
- Suggest which age bracket requires less focus from bike manufacturers based on the analysis.

**C. Reporting**
- Create a visually appealing dashboard with at least three slicers.
- Analyze the behavior of European middle-age singles regarding bike purchases.
- Identify which academic qualification leads to higher earnings.

## Data Cleaning and Formatting
Data cleaning and formatting included:

1. **Removing Duplicates**: 
   - Highlighted the dataset to identify duplicates and blanks.
   - Used the "Remove Duplicates" feature, with ID as the primary key.

2. **Replacing Values**: 
   - Utilized Find and Replace to convert "M" to "Male" and "F" to "Female" in the gender column, and "M" to "Married" and "S" to "Single" in the marital status column.

3. **Income Formatting**: 
   - Adjusted the income column to display as currency with no decimal places.

4. **Age Grouping**: 
   - Created a new column for age brackets using the following formula:
     ```
     =IF(L2<=30,"Adolescent",IF(L2<=54,"Middle Age",IF(L2>=55,"Old")))
     ```

## Data Exploration
Pivot Tables were utilized to explore the cleaned dataset, addressing the initial questions. Charts, particularly line charts, aided in identifying the age bracket requiring less attention from bike manufacturers.

## Data Visualization and Insights
Visual representations included bar and line charts created in Microsoft Excel. Key findings included:

- Average income of European middle-age singles and their purchasing patterns.
- Graduate degree holders exhibited the highest average income of $70,000.

### Dashboard Insights
1. **European Middle Age Singles**: 
   - This demographic travels fewer miles despite a bike purchase count of around 70, indicating they are less likely to commute.

2. **Income by Qualification**: 
   - Graduates demonstrated the highest average income, suggesting a targeted marketing approach for this group.

## Conclusion
The analysis provided valuable insights into bike purchasing behaviors across different demographics:

- Identified the age bracket requiring less focus from manufacturers.
- Examined the behavior of European middle-age singles regarding bike purchases.
- Determined which academic qualifications correlate with higher earnings.

## Recommendations
1. **Marketing Focus**: 
   - Shift marketing efforts from the middle-age group to adolescents and seniors, who have shown lower purchase counts.

2. **Targeting Middle Age Singles**: 
   - Consider that European middle-age singles may prefer bikes for local errands rather than commuting, indicating a potential market for lifestyle-oriented products.

3. **Focus on Graduates**: 
   - Given their higher average income, manufacturers should specifically target graduates, particularly those in the Pacific Region.

By aligning marketing strategies with identified consumer behaviors and demographics, bike manufacturers can optimize their sales efforts effectively. 

---

For further inquiries or details regarding this analysis, please contact the team.
