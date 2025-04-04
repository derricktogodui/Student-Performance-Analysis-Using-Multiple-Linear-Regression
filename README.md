# Student-Performance-Analysis-Using-Multiple-Linear-Regression

## Analysis of Student Performance Based on Attendance and Exercise Scores
### Prepared by: Derrick Kwaku Togodui

## Introduction
This report presents an analysis of the relationship between student attendance, exercise scores, and overall semester performance. The goal was to determine whether attendance and exercise participation can predict student performance and to derive insights that can help improve academic outcomes.

## Data Overview
The dataset consisted of 145 students with the following key variables:
1. Attendance Percentage (weekly class attendance rate)
2. Average Exercise Score (average score from class exercises)
3. Overall Semester Performance (final score for the semester)
   Data was cleaned to exclude students with missing values and zero scores.

## Key Findings
### Correlation Analysis
A heatmap analysis showed the following relationships:
1. Attendance vs. Overall Performance: r = 0.411 (moderate positive correlation)
2. Exercise Score vs. Overall Performance: r = 0.838 (strong positive correlation)
3. Attendance vs. Exercise Score: r = 0.463 (moderate positive correlation)
This suggests that while both attendance and exercise scores influence overall performance, exercise scores have a much stronger impact.

### Regression Model Results
A multiple linear regression model was developed with Attendance Percentage and Average Exercise Score as predictors of Overall Semester Performance.
Model Coefficients
1. Intercept: 1.34
2. Attendance Coefficient: 0.076
3. Exercise Score Coefficient: 2.205

#### This means:
1. For every 1% increase in attendance, a student’s semester score increases by 0.076 points (minimal effect).
2. For every 1-point increase in exercise scores, the semester performance improves by 2.205 points (significant effect).
   Model Performance
3. R-squared: 0.535 (53.5% of the variance in performance is explained by attendance and exercise scores)
4. Mean Squared Error (MSE): 161.45 (average squared difference between actual and predicted performance)

### Interpretation of Findings
1. Exercise scores are a stronger predictor of performance than attendance.
2. Attendance alone does not significantly impact performance but may indirectly contribute by improving engagement in exercises.
3. The model is moderately effective (R² = 0.535), suggesting that other factors (e.g., study habits, prior knowledge) influence performance.

## Recommendations
1. Encourage Active Participation in Exercises
  - Since exercise scores strongly correlate with performance, teachers should emphasize frequent, high-quality exercises.
2. Improve Engagement Rather Than Just Attendance
  - Instead of enforcing strict attendance policies, focus on interactive learning to keep students engaged.
3. Incorporate Additional Factors
  - Future analysis should include quiz scores, homework completion, and past performance to improve prediction accuracy.
4. Personalized Support for Low-Performing Students
  - Identify students with low exercise scores and provide targeted academic support.

## Conclusion
This study highlights the importance of exercise-based learning in improving student performance. While attendance plays a role, the quality of participation (exercise performance) matters more than just being present.
Moving forward, interventions should focus on engaging students in exercises and providing additional academic support to maximize their success.
