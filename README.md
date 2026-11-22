 Student Performance Analysis

1. Case Study Title
Student Performance Analysis Using Google Sheets

2. Problem Statement
An engineering college maintains student records containing attendance percentages, marks and department details. Analysing these records manually is time-consuming and makes it difficult to identify students with poor academic performance. This case study uses Google Sheets to organize, analyse and visualize student data. It helps identify top performers, compare department-wise results and find students who require academic support.

 3. Objectives
- To organize student records in a spreadsheet.
- To calculate total and average marks.
- To identify the highest and lowest marks.
- To analyse student attendance percentages.
- To sort and filter student records.
- To compare department-wise academic performance.
- To create charts and visualizations.
- To identify students who need academic support.

4. Dataset Description
The dataset consists of 12 students from four departments: AIDS, CSE, IT and ECE.

| Field | Description |
|---|---|
| Student ID | Unique identification number of each student |
| Name | Name of the student |
| Department | Department of the student |
| Attendance % | Percentage of attendance |
| Marks | Marks obtained by the student |

Three helper columns were added using formulas: **Result** (Pass/Fail), **Attendance Status** (Below 75% / OK) and **Needs Support** (Yes/No).

The workbook is named **Student_Performance_Analysis** and contains these sheets: Data, PartA_Structure, PartB_Formulas, Sorted, Filtered, Grouped, DeptSummary, Charts, HeatMap and Interpretation.

 5. Spreadsheet Functions Used

| Function | Purpose |
|---|---|
| `SUM()` | Calculates total marks |
| `AVERAGE()` | Calculates average marks and average attendance |
| `MAX()` | Finds the highest marks |
| `MIN()` | Finds the lowest marks |
| `COUNT()` | Counts the total number of students |
| `IF()` | Identifies Pass (marks 50 or above) or Fail, and attendance below 75% |
| `COUNTIF()` / `COUNTIFS()` | Counts students by department, result and marks range |
| `AVERAGEIF()` | Calculates department-wise average marks and attendance |
| `MAXIFS()` / `MINIFS()` | Finds department-wise highest and lowest marks |
| `RANK()` | Ranks students by marks |
| `CORREL()` | Measures the relationship between attendance and marks |
| `INDEX()` / `MATCH()` | Looks up the top department and top performers |

 6. Data Analysis Techniques Performed
1. **Sorting:** Students were arranged in descending order of marks.
2. **Filtering:** Students scoring above 80 marks were identified (5 students).
3. **Grouping:** Students were grouped by department, with a group average for each.
4. **Conditional Formatting:** Marks above 85 are highlighted in green; attendance below 75% is highlighted in red.
5. **Department-wise Summary:** Student count, average marks, average attendance, highest and lowest marks, and pass percentage were calculated for each department.
6. **Performance Analysis:** Students with marks below 60 or attendance below 75% were flagged for additional academic support.

 7. Charts and Visualizations Created
- **Bar Chart:** Department-wise average marks.
- **Pie Chart:** Percentage distribution of students across departments.
- **Histogram:** Distribution of student marks (bins of 10 marks).
- **Heat Map:** Colour scale (red = low, green = high) showing student marks across departments.

8. Important Observations
- Total number of students: 12
- Total marks obtained: 897
- Overall average marks: 74.75
- Highest mark: 94 (Divya)
- Lowest mark: 48 (Anitha)
- Number of students who passed: 11
- Number of students who failed: 1 (Anitha)
- Students with attendance below 75%: 2 (Anitha 68%, Rahul 70%)
- Overall average attendance: 83.33%
- Department-wise average marks:

| Department | Students | Average Marks | Average Attendance % |
|---|---|---|---|
| IT | 3 | 78.00 | 83.67 |
| AIDS | 3 | 76.67 | 85.00 |
| CSE | 3 | 74.33 | 83.67 |
| ECE | 3 | 70.00 | 81.00 |

- The IT department achieved the highest average marks (78.00); ECE recorded the lowest (70.00).
- The top three performers are Divya (94), Meena (91) and Vijay (89).
- Attendance and marks show a very strong positive relationship (correlation ≈ 0.97).
- Anitha, Rahul and Manoj require additional academic attention. Karthik (65 marks) is the lowest scorer in IT and may be monitored.

 9. Conclusion
The Student Performance Analysis case study demonstrates how Google Sheets can be used effectively to organize, analyse and visualize student academic data. By applying spreadsheet functions, sorting, filtering, conditional formatting and charts, student performance and attendance patterns can be understood easily. The analysis identifies the IT department as the highest-performing department, shows that higher attendance goes with higher marks, and highlights students who require additional academic support. Overall, this study shows how spreadsheet tools simplify data analysis and support better academic decision-making.
