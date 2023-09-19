# PySpark-KNN

# PySpark k-Nearest Neighbors (k-NN) Project

## Overview

This project demonstrates how to implement k-Nearest Neighbors (k-NN) classification using PySpark on the Iris dataset. K-NN is a versatile machine learning algorithm used for both classification and regression tasks. In this project, we use PySpark, a powerful framework for distributed data processing, to build and evaluate a k-NN model.

![Iris Flowers](images/iris-flowers.png)

![PySpark for KNN Project Google Slides](https://docs.google.com/presentation/d/1ARbGWvwN3wITuDLKiwxUqz_PzmanvEydkJ9GUmo0Oy4/edit?usp=drive_link)


## Prerequisites

Before running the project, make sure you have the following installed:

- [Python](https://www.python.org/) (3.6 or higher)
- [Apache Spark](https://spark.apache.org/downloads.html)
- Python libraries: PySpark, scikit-learn

You can install the Python libraries using pip:

```bash
pip install pyspark scikit-learn
<img width="1010" alt="Screenshot 2023-09-18 at 7 50 18 PM" src="https://github.com/franketang/PySpark-KNN/assets/29631514/a23e880c-9daa-46f0-a011-3487205747e0">


Ensure that you have Apache Spark properly installed and configured on your system.

Run the Python script by submitting job on dataproc
<img width="1002" alt="Screenshot 2023-09-18 at 7 51 19 PM" src="https://github.com/franketang/PySpark-KNN/assets/29631514/a8b78fe5-e2ff-4f85-9a4e-2e75d08a421d">


View the accuracy of the k-NN model on the Iris dataset.
Project Structure
The project structure is organized as follows:

bash
Copy code
pyspark-knn-project/
  ├── pysparkknn.py  # Main Python script
  ├── README.md               # Project documentation (you are here)
  └── images/                 # Images and visualizations

Usage
Modify the pysparkknn.py script to customize the k-NN model or dataset.
Experiment with different hyperparameters, such as the number of neighbors (k), to optimize model performance.
Explore additional evaluation metrics beyond accuracy for a more comprehensive analysis.

Results
The project demonstrates how to build a k-NN classification model using PySpark and evaluate its performance on the Iris dataset. The accuracy achieved on the test data is reported in the console output.
<img width="1007" alt="Screenshot 2023-09-18 at 8 07 43 PM" src="https://github.com/franketang/PySpark-KNN/assets/29631514/0c5060dd-042f-410b-a69e-8d1b6ba1e315">



Contributing
Contributions are welcome! Feel free to open issues, submit pull requests, or provide suggestions to improve this project.

License
This project is licensed under the MIT License. See the LICENSE file for details.


