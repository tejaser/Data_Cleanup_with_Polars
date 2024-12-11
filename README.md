# Data Cleanup with Polars

This repository demonstrates how to efficiently clean and preprocess data using the Polars library, a fast and memory-efficient DataFrame library written in Rust. Polars is an excellent alternative to Pandas for handling large datasets due to its performance and scalability.

## Features

- Leverages Polars for high-performance data manipulation.

- Includes examples of common data cleanup tasks such as:

- Handling missing values.

- Renaming and filtering columns.

- Merging and grouping data.

- Optimizing data for analysis.

- Scalable to large datasets.

- Easy-to-understand scripts suitable for beginners and advanced users alike.

## Setup and Installation

### Pre requisite 
- Enusre you have Python 3.10 or later
- Anaconda or Miniconda installed

### Setup 

1. Create conda environment using below command in your directory
   `conda create -p venv python=3.11`
2. post installation activate the environment
   `conda activate <path to directory>`
3. Install depdendency using `pip` command
   `pip install -r requirements.txt`
4. *Optional*: Install `Jupyter notebook`

## Usage

- Please refer to the Python notebook `data_cleanup.ipynb` for code reference
- Supporting blog is written on Medium at this [link](https://medium.com/@Tp70227/effortless-data-cleaning-in-python-with-polars-a-step-by-step-guide-d4282c7a8b4b)

## Contributing

Contributions are welcome! To contribute:

- Fork the repository.

- Create a new branch:

- git checkout -b feature/your-feature-name

- Make your changes and commit them:

`git commit -m "Add your feature description"`

- Push to your branch:

`git push origin feature/your-feature-name`

- Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
