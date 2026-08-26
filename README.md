# Sorting Algorithms: Implementation & Time Analysis

A Jupyter notebook implementing and benchmarking five classic sorting algorithms in Python:

- Bubble Sort
- Selection Sort
- Insertion Sort
- Merge Sort
- Quick Sort

## Features
- Clean, from-scratch Python implementations of each algorithm
- Interactive user input for testing custom lists
- Real runtime measurement using Python's `time` module
- Time complexity (best / average / worst case) and space complexity for each algorithm
- Side-by-side runtime comparison on a shared random dataset, with a bar chart visualization
- Summary table comparing complexity, stability, and in-place behavior

## Getting Started
1. Clone the repo
2. Install dependencies: `pip install jupyter matplotlib`
3. Open `sorting_algorithms_analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab
4. Run the cells top to bottom — each algorithm cell uses sample data by default; swap in `get_user_list()` (no arguments) to type your own numbers

## Complexity Summary

| Algorithm      | Best Case   | Average Case | Worst Case  | Space       |
|----------------|-------------|---------------|-------------|-------------|
| Bubble Sort    | O(n)        | O(n²)         | O(n²)       | O(1)        |
| Selection Sort | O(n²)       | O(n²)         | O(n²)       | O(1)        |
| Insertion Sort | O(n)        | O(n²)         | O(n²)       | O(1)        |
| Merge Sort     | O(n log n)  | O(n log n)    | O(n log n)  | O(n)        |
| Quick Sort     | O(n log n)  | O(n log n)    | O(n²)       | O(log n)    |

## License
MIT
