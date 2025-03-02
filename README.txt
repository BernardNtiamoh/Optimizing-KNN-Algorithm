# Optimizing K-Nearest Neighbors (KNN) Algorithm

In this repository, I explore and implement techniques to optimize the **K-Nearest Neighbors (KNN)** algorithm using **R**. The focus is on varying the distance metrics and centroid measures to determine the combination that achieves the best performance across all instances.

## Key Features of the Project
- **Distance Metrics**: Experimented with **46 different distance metrics** to evaluate their impact on the performance of the KNN model.
- **Centroid Measures**: Analyzed **8 different measures of centroids** to find the most effective way to compute representative points for clusters.
- **Performance Optimization**: Identified the best-performing combinations of distance metrics and centroid measures for various datasets and scenarios.

## Goals
The main objectives of this project are to:
1. Investigate how different distance metrics affect the accuracy and robustness of the KNN algorithm.
2. Evaluate the influence of various centroid measures on the overall performance of the model.
3. Provide insights and recommendations for selecting the optimal KNN configuration for different datasets.

## Structure of the Repository
The repository is organized as follows:
- **`data/`**: Contains sample datasets used for testing and evaluation.
- **`scripts/`**: R scripts implementing the KNN algorithm with customizable distance metrics and centroid measures.
- **`results/`**: Summarized results and performance metrics for various configurations.
- **`README.md`**: Overview of the project (this file).

## Techniques Used
- Implemented custom distance metrics using R functions for greater flexibility.
- Integrated multiple centroid computation methods (e.g., mean, median, geometric median).
- Cross-validation to assess the performance of different configurations.
- Visualized results with detailed plots to compare the performance of varying setups.

## Tools and Libraries
This project was developed using **R** and leverages the following key libraries:
- `caret` for training and evaluating the KNN model.
- `dplyr` for data manipulation.
- `ggplot2` for data visualization.
- `tidyr` for data wrangling.

## Getting Started
### Prerequisites
Make sure you have **R (version 4.0 or higher)** and the necessary libraries installed. Install required packages using:

```R
install.packages(c("caret", "dplyr", "ggplot2", "tidyr"))
```

### Running the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/knn-optimization.git
   cd knn-optimization
   ```
2. Run the R scripts in the `scripts/` folder to reproduce the analysis and results:
   ```R
   source("scripts/knn_optimization.R")
   ```

3. Review the results and visualizations generated in the `results/` directory.

## Results
- The optimal combination of distance metric and centroid measure varies across datasets and specific scenarios.
- The project includes detailed analysis, plots, and tables summarizing the findings.

## Contributing
Contributions are welcome! If you’d like to improve the code, add new metrics or centroid measures, or suggest enhancements, feel free to fork the repository and submit a pull request.

## Acknowledgments
- Thanks to the R community for providing tools and resources that made this project possible.
- Inspired by the need to enhance the traditional KNN algorithm for diverse use cases.

---

