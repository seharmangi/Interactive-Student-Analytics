# Interactive Student Analytics 

This project contains a Jupyter Notebook that analyzes student activity data collected from a SQL database. The database content was generated using the Faker library to simulate realistic student, course, and activity records for demonstration and testing purposes.

# Note: Since interactive widgets and plots like the activity distribution chart and the interactive dashboard
# won't display properly on GitHub, screenshots of these dashboard features
# have been added to the repository to illustrate the interactive visualizations.


## Features

- Extracts course and student activity data using SQL queries.
- Provides interactive visualizations to explore average student scores by course.
- Displays activity heatmaps showing the distribution of activities by hour.
- Uses ipywidgets for interactive dropdowns to enhance user experience.
- Helps identify patterns in student engagement and performance.

## Getting Started

1. Ensure you have Python installed with the following packages: pandas, matplotlib, seaborn, ipywidgets, and a suitable SQL connector (e.g., sqlite3).
2. Connect the notebook to your database by updating the connection parameters.
3. Run the notebook cells sequentially to generate visualizations and interact with the dashboard.
4. Use the dropdown menu to select courses and view average scores by student.
5. Analyze the heatmap to understand peak activity times.

## Data Source

The SQL database data was generated using the Faker library to create a synthetic dataset of students, courses, activities, timestamps, and scores. This allows safe experimentation without real personal data.

## Intended Users

This notebook is designed for educators, data analysts, and researchers interested in understanding student behaviors and course engagement through data-driven insights.

## License

This project was created out of my interest in the education sector and a passion for learning analytics. It is open for educational and non-commercial use. Feel free to adapt it for your own learning analytics needs.


