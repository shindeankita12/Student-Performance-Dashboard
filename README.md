Student Performance Dashboard – Power BI

 Project Overview

This project presents an interactive **Student Performance Dashboard** built using Power BI.
It analyzes student academic performance, attendance, and behavior across different classes, subjects, and terms.

The goal is to transform raw data into meaningful insights using **data modeling, DAX, and visual storytelling**.

 Dashboard Preview:---
<img width="1309" height="731" alt="image" src="https://github.com/user-attachments/assets/039183aa-2751-43bf-9d9c-272d2381a4b3" />

 Dataset Description:--

The project uses four datasets:

* **Students.csv**
  Contains student details like ID, Name, Gender, Class, and Section.

* **Scores.csv**
  Includes subject-wise marks, exam types, and terms.

* **Attendance.csv**
  Tracks daily attendance with status (Present/Absent).

* **Behavior.csv**
  Records student behavior types and notes.

 Data Modeling:---

* Established relationships using **StudentID** as the key.
* Followed a structured model:

  * Students → Dimension table
  * Scores, Attendance, Behavior → Fact tables
* Cleaned data:

  * Corrected data types
  * Handled missing/null values

 Key DAX Measures:---

* **% Score** = Score / MaxScore
* **Average Score**
* **Attendance %**
* **Behavior Count**
* **Performance Category** (High / Medium / Low)

 Dashboard Features:---

###  Academic Analysis

* Bar Chart: Average Score by Subject & Class
* Line Chart: Performance Trend by Term

###  Behavioral Insights

* Donut Chart: Behavior Type Distribution

### Student-Level Data

* Table with conditional formatting:

  * Green → High scores (>80%)
  * Red → Low scores (<40%)

### KPIs

* Total Students
* Average Score
* Attendance %

---

 Interactivity:---

* Slicers:

  * Class, Section, Subject, Term
* Drillthrough:

  * Detailed student-level analysis page
* Tooltips:

  * Additional insights on hover
* Bookmarks:

  * Toggle between Academic and Behavioral views

 Additional Feature:---

* Mobile-friendly layout for better accessibility

 Deliverables:---

* Power BI file (**.pbix**)
* Interactive dashboard
* Insights derived from data


Tools & Technologies:---

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling



---
