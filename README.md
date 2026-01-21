# Project Graph: Social Network Analysis (Facebook 100)

This project performs an analysis of social network graphs using the **Facebook 100 (fb100)** dataset. It explores the structure of university social networks and evaluates the correlation between network connections and node attributes (such as Dorm, Year, and Major) using Normalized Mutual Information (NMI) scores.

## 📂 Project Structure

- **`projet.ipynb`**: The main Jupyter Notebook containing the code for:
  - Loading graph data from GML files.
  - Visualizing network layouts.
  - Computing graph metrics.
  - Validating community structure against ground truth attributes using NMI.
- **`data/`**: (Required) Directory containing the GML files (e.g., `Caltech36.gml`, `MIT8.gml`, etc.).

## 🛠️ Dependencies

To run this project, you will need **Python 3** and the following libraries:

- **NetworkX**: For graph manipulation and analysis.
- **Matplotlib**: For graph visualization.
- **NumPy**: For numerical operations.
- **Jupyter**: To run the notebook.

You can install the dependencies using pip:

pip install networkx matplotlib numpy jupyter

Usage
Clone or download this repository.

Setup Data: Ensure you have the .gml files from the Facebook 100 dataset.

Configure Path: Open projet.ipynb and locate the configuration cell:

Python

# Update this path to match your data location
data_folder = r'path/to/your/fb100/data'
Note: The notebook currently defaults to C:\Users\TEMMMAR\Desktop\M2 TRIED\projet Graph\fb100\data. Please update this to your local directory.
