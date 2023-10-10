# Copilot Data Engineering Workshop Starter Code

Welcome to the Copilot Data Engineering Workshop! This repository provides you with a starter codebase to experiment with various data engineering tasks using Python. 

## Prerequisites

Before you begin, make sure you have the following prerequisites installed on your system:

- Python 3 (Python 3.6 or higher is recommended)
- `pip` (Python package manager)

## Getting Started

Follow these steps to set up your environment and run the provided data engineering script:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/antoprince001/copilot-dataengineering-python/
   ```

2. Navigate to the project directory:

   ```bash
   cd copilot-dataengineering-python
   ```

3. Create a virtual environment to isolate project dependencies:

   ```bash
   python3 -m venv env
   ```

4. Activate the virtual environment:

   ```bash
   source env/bin/activate
   ```

5. Install the required Python packages from the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

## Running the ETL Script

Now that you have set up your environment, you can run the ETL (Extract, Transform, Load) script to experiment with data engineering tasks.

To run the ETL script, execute the following command:

```bash
python3 etl.py
```

## Working with `transform.py`

The `transform.py` file is a key component of your data engineering pipeline. It's where you can apply various transformations to your data to prepare it for analysis. Here are some steps to get started with `transform.py`:

1. Open the `transform.py` file from `src/jobs` folder in your code editor.

2. Review the existing code and understand the data transformations that are already implemented.

3. Modify the `transform.py` script as needed for your specific use case. You can add, remove, or customize data transformation functions to suit your data engineering requirements.

4. Optionally, you can consider using [Test-Driven Development (TDD)](https://antoprince001.medium.com/test-driven-development-in-pyspark-3b48f77bca06) principles to ensure the correctness of your data transformations. Write unit tests for your transformation functions in a separate test_transform.py file under `tests/jobs` folder and run the tests regularly.

5. To execute the test suite using pytest, execute the following command
```bash
pytest tests/jobs/test_transform.py

```

6. Make use of Copilot's code suggestions and autocompletion features to make your data transformation tasks more efficient and productive.

## Working with `analysis.ipynb`

The `analysis.ipynb` file is a Jupyter Notebook where you can perform in-depth data analysis and visualization on your transformed data. Here's how to work with `analysis.ipynb`:

1. Open the `analysis.ipynb` notebook using a Jupyter Notebook environment or any compatible tool.

2. Review the existing code to load the transformed data into the notebook.

3. Explore the data, perform statistical analysis, and create visualizations to gain insights from your data.

4. Feel free to experiment with copilot for different analysis techniques and visualizations to extract valuable information from your data.

5. Optionally, the tasks in analysis.ipynb can also be done by creating `analysis.py` file. Choose the option that best suits your workflow and preferences for data analysis.

Happy data engineering with Copilot! 🚀📊
