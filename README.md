# Intro Repository

This repository contains a series of Jupyter notebooks and supporting files for an introductory exploration of time series analysis, data processing, and visualization using Python. The materials are intended for learners who are new to data science and scientific computing.

## Repository Structure

```
Intro/
├── data/                        
│   ├── sst_timeseries.csv       # Sea Surface Temperature time series data
│   └── ...                      # Additional datasets
├── notebooks/                   
│   ├── P1_data_cleaning.ipynb   # Data cleaning and preprocessing examples
│   ├── P2_visualization.ipynb   # Basic plotting and visualization
│   ├── P3_RAME_timeseries_csv.ipynb  # Time series analysis of SST data
│   └── ...                      # Other introductory notebooks
├── requirements.txt             # Python dependencies
└── README.md                    # Project overview and instructions
```

## Prerequisites

- **Python 3.8+**
- **Jupyter Notebook** or **JupyterLab**
- Libraries listed in `requirements.txt` (install via `pip install -r requirements.txt`)

## Installation

1. Clone the repository:  
   git clone https://github.com/Indungulo/Intro.git  
   cd Intro  
2. (Optional) Create and activate a virtual environment:  
   python3 -m venv venv  
   source venv/bin/activate      # on Windows: venv\Scripts\activate  
3. Install dependencies:  
   pip install -r requirements.txt  

## Usage

1. Launch Jupyter Notebook or Lab:  
   jupyter notebook  
   or  
   jupyter lab  
2. Navigate to the `notebooks/` directory and open any notebook.  
3. Follow the step-by-step instructions in each notebook to explore data processing, visualization, and analysis techniques.

## Notebooks Overview

- **P1_data_cleaning.ipynb**: Introduction to reading, cleaning, and preparing raw data.  
- **P2_visualization.ipynb**: Fundamentals of plotting with Matplotlib and Plotly.  
- **P3_RAME_timeseries_csv.ipynb**: Time series analysis workflow applied to sea surface temperature (SST) data.

## Data Sources

The primary dataset (`sst_timeseries.csv`) contains daily sea surface temperature readings from 2007-01-01 to 2024-10-22.

## Contributing

Contributions are welcome. To contribute:

1. Fork this repository.  
2. Create a new branch (`git checkout -b feature/your-feature`).  
3. Commit your changes (`git commit -m "Add feature"`).  
4. Push to the branch (`git push origin feature/your-feature`).  
5. Open a pull request.  

Please ensure that your code is well-documented and follows PEP8 conventions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
