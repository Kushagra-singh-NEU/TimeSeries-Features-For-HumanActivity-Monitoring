# TimeSeries-Features-For-HumanActivity-Monitoring

## Objective

The objective is to extract time series features for human activity monitoring using accelerometer data for walking, running, climbing up, and climbing down.

## Dataset

The human activity data for 15 subjects can be accessed [here](dataset_link). Consider accelerometer data for all 15 subjects for the specified activities.

## Task 1: Natural Visibility Graph (NVG) and Horizontal Visibility Graph (HVG)

1. Applied NVG and HVG to the accelerometer data.
2. Computed average degree, network diameter, and average path length.
3. Selected a sample size of 1024 data points (from 1000 to 2024) for each of the 15 time series.
4. Tabulated the results.
5. Generated scatter plots: average degree vs network diameter, color points according to walking and running.
6. Generated scatter plots: average degree vs network diameter, color points according to climbing up and climbing down.

### Sample Output Table

| Method | Subject | Accelerometer Axis | Average Degree | Network Diameter | Average Path Length | Activity |
|--------|---------|--------------------|----------------|-------------------|----------------------|----------|
| HVG/NVG | 1 to 15 | X or Y or Z | Walking or Running or Climbing Up or Climbing Down |

## Task 2: Permutation Entropy and Complexity

1. Computed permutation entropy and complexity for the accelerometer data.
2. Varied parameters: Embedded Dimension (3, 4, 5, 6), Embedded Delay (1, 2, 3), Signal Length (1024, 2048, 4096).
3. Generated scatter plots: permutation entropy vs complexity, color points according to walking and running.
4. Generated scatter plots: permutation entropy vs complexity, color points according to climbing up and climbing down.

### Sample Output Table

| Subject | Accelerometer Axis | Signal Length | Dimension | Delay | Permutation Entropy | Complexity | Activity |
|---------|--------------------|---------------|------------|-------|----------------------|-------------|----------|
| 1 to 15 | X or Y or Z | 1024 or 2048 or 4096 | 3 or 4 or 5 or 6 | 1 or 2 or 3 | Walking or Running or Climbing Up or Climbing Down |

