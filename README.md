# Text Mining and Customer Clustering with TripAdvisor Reviews

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org)  
[![Pandas](https://img.shields.io/badge/Pandas-Used-green)](https://pandas.pydata.org)  
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Used-orange)](https://scikit-learn.org)  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Used-red)](https://matplotlib.org)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)  

This is one of my master's projects, focusing on the practice of **text mining** using a dataset inspired by the **TripAdvisor** website. The primary aim is to **cluster customers** based on their **comments** and reviews left on the platform. The project was implemented using **Python 3** and the **PyCharm IDE**.

Due to data sharing restrictions, the original dataset cannot be included, but all steps, data features, and methodologies are thoroughly documented in the provided report file.

## 📊 About the Dataset

The dataset is inspired by **TripAdvisor**, a well-known travel agency company. It includes **1,850 textual data entries** (documents), each containing reviews and ratings from previous travelers regarding various hotels. To optimize performance and reduce computational load, only the **first 100 documents** were randomly selected as the input data. This subset maintains the essence of the original dataset without following any specific order.

- **Data Type**: Textual reviews and ratings.
- **Source**: TripAdvisor (anonymized and inspired).
- **Size**: 100 documents (subset from 1,850).
- **Purpose**: Clustering based on customer feedback.

## 🗺️ Project Sections

The project is structured into the following sections, as detailed in the report:

1. **Section 1: General Objectives of the Chapter**  
   Outlines the overall goals and scope of the text mining project.

2. **Section 2: Dataset Characteristics**  
   Describes the dataset's features, structure, and key attributes.

3. **Section 3: Programming Language and IDE Description**  
   Details the use of Python 3 and PyCharm IDE for implementation.

4. **Section 4: Data Cleansing and Clustering Phase**  
   Covers data preprocessing, cleansing techniques, and the application of clustering algorithms.

5. **Section 5: Presentation and Analysis of Results**  
   Presents the clustering outcomes, visualizations, and analytical insights.

## 🛠️ Technologies and Packages

The project leverages the following Python packages for data manipulation, analysis, and visualization:

- **Pandas**: For data handling and manipulation.
- **NumPy**: For numerical computations.
- **Scikit-learn (sklearn)**: For machine learning algorithms, including clustering.
- **Matplotlib**: For plotting and visualizations.
- **SciPy**: For scientific computing, supporting advanced mathematical functions.

## 🔍 Clustering Methods

Two primary clustering techniques were employed to group customers based on their textual comments:

- **K-Means Clustering**: A centroid-based algorithm that partitions data into k clusters by minimizing variance within each cluster.
- **Dendrogram (Hierarchical Clustering)**: Used for visualizing the hierarchical structure of clusters, often via linkage methods to show relationships between data points.

## 📁 Repository Structure

- `reports/`: Detailed project report and documentation.
- `src/`: Source code files for data processing and clustering.
- `README.md`: This file.

## 🚀 Getting Started

1. Ensure you have **Python 3.8+** installed. Download from [python.org](https://www.python.org).
2. Install the required packages:  
   ```bash
   pip install pandas numpy scikit-learn matplotlib scipy
   ```
3. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/Text-Mining-TripAdvisor.git
   ```
4. Open the project in **PyCharm IDE** or run the scripts/notebooks to explore the text mining and clustering processes.

> **Note**: The dataset is not provided; refer to the report for data characteristics and use a similar textual dataset for experimentation.

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, suggest improvements, or add new analyses. Please submit pull requests with detailed descriptions.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*If this project inspires your research or studies, please give it a ⭐ and share your feedback!* 🚀  

For more details, check the full report in the `reports/` directory. If you have questions, open an issue in this repository.
