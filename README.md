# Singular Value Decomposition (SVD) Project

This project explores the fundamental concepts of Singular Value Decomposition (SVD) through practical implementation and applications. The main highlight is a custom SVD function that does not rely on built-in numpy functions, which is validated against numpy's implementation.

## Features

- **Custom SVD Implementation**: A Python function for performing SVD on 2D arrays, complete with eigenvalue computations and sorting.
- **Error Checking**: A method to compare the custom SVD results with numpy's built-in SVD to ensure accuracy.
- **Orthogonal Procrustes Analysis**: Application of SVD in aligning point clouds, with a focus on transformation matrices.
- **Image Compression**: Demonstration of using SVD for image compression, showcasing the reduction of image ranks.
- **Applications**: Detailed exploration of the practical applications of SVD, particularly in the field of data analysis and machine learning.

## Getting Started

### Prerequisites

- Python 3.x
- NumPy
- Matplotlib
- OpenCV (for image processing)

### Installation

Clone this repository to your local machine using:

```bash
git clone https://github.com/megamiii/SingularValueDecomposition.git
```

The Jupyter notebook SVD.ipynb contains a cell with instructions to install all required dependencies. You can install the required packages by executing this cell. Alternatively, you can install the required packages manually with the following command:

```bash
pip install numpy matplotlib opencv-python
```


### Usage
Open the Jupyter notebook (SVD.ipynb) in your preferred environment, such as Jupyter Lab or Google Colab.
```bash
jupyter notebook SVD.ipynb
```

## Files in Repository
- `SVD.ipynb:` The main Jupyter notebook containing the SVD algorithm and its applications.
- `cameraman.jpg:` Sample image used for compression demonstration.
- `input.ply` and `target.ply`: Point cloud data files for the Orthogonal Procrustes analysis.