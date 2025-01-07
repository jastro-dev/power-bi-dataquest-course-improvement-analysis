# Dataquest Course Improvement Analysis

A Power BI project focused on identifying and improving underperforming courses at Dataquest using quantitative metrics such as lesson completion rates and Net Promoter Scores (NPS).

## Project Structure

- `Power BI Final Project - Complete.pbix` - Power BI report containing interactive dashboards and detailed analyses.
- `data/` - Input datasets used in the analysis:
  - `lesson_progress.csv` - Tracks lesson progress, including start/completion times and statuses.
  - `nps_data.csv` - Contains NPS survey scores and response details.
  - `course_lessons.csv` - Maps lessons to their corresponding courses.

## Implementation Notes

This project utilized Power BI for data modeling, analysis, and visualization. The analysis identifies actionable insights and supports Dataquest's goal of improving learner engagement and satisfaction.

### Key Features

- Comprehensive dashboards for lesson completion and NPS analyses.
- Dynamic filtering options, such as course-specific slicers.
- Visual KPIs to monitor trends and compare performance to goals.

### Implemented Analyses

1. **Lesson Completion Rate Analysis**
   - Overall lesson completion rate KPI: **76.49% (Goal: 75%)**.
   - Monthly trends and scatter plots showing lessons started vs. completion rates.
   - Completion rate distribution histogram.

2. **Net Promoter Score (NPS) Analysis**
   - Current NPS: **62.78 (Goal: 65)**.
   - Monthly trends of NPS scores and survey responses.
   - Scatter plots of NPS vs. response amounts with logarithmic scaling.
   - Histogram of survey scores (1–10).

3. **Recommendations**
   - Five courses identified for improvement based on low NPS and completion rates:
     1. **Course ID 58**
     2. **Course ID 18**
     3. **Course ID 52**
     4. **Course ID 100**
     5. **Course ID 59**
   - Detailed metrics table highlighting average completion rates, NPS scores, and response amounts.
   - Recommendations focus on courses with the greatest potential for KPI improvements.

### Development Environment

- **Data Modeling and Visualization**: Power BI Desktop
- **Data Transformation**: Power Query and DAX (Data Analysis Expressions)
- **Data Sources**:
  - Lesson progress data
  - NPS survey data
  - Course-to-lesson mapping

### Key Findings

- Completion rates exceeded goals; however, certain courses still showed significant room for improvement.
- NPS scores fell slightly short of targets, suggesting a need for targeted enhancements to learner experiences.
- Prioritizing improvements for the recommended courses will maximize impact on key performance indicators.

### How to Use

1. Download the `dataquest_analysis.pbix` file.
2. Open the file in Power BI Desktop to explore interactive dashboards.
3. Utilize slicers and filters to focus on specific courses or trends.
4. Review the "Recommendations" page for detailed insights into course improvement opportunities.

---

This project demonstrates the value of data-driven analysis in enhancing course quality and ensuring learner satisfaction.
