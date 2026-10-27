# ECON 3916 — Problem Set 2: The Survey That Wasn't Random

## Project Overview

This project examines how survey results can be misleading when the people who respond are not representative of the overall population. Using Python in Google Colab, I simulated customer satisfaction before and after a product redesign to see how nonresponse bias affects the results.

## Main Findings

The observed survey satisfaction increased from 3.60 before the redesign to 4.30 afterward, suggesting an improvement of about 0.70 points. However, the true improvement in the simulated population was only 0.10 points, from 3.30 to 3.40.

The difference occurred because customers with higher satisfaction scores were more likely to respond, especially after the redesign.

## Methods Used

- **Population Simulation:** Created two simulated populations of 50,000 users.
- **Bootstrap Confidence Intervals:** Estimated uncertainty using manual bootstrap resampling and SciPy.
- **Coverage
