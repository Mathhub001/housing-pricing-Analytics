# housing-pricing-Analytics
Pricing Analytics



## Project Structure

- `data/`: Contains the CSV file generated from the collected data.
- `notebooks/`: Contains the Jupyter notebook for data visualization.

## Setup Instructions

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- matplotlib (for visualization)


### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/income-spending-survey.git
    cd income-spending-survey
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Ensure MongoDB is installed and running on your local machine or connect to a MongoDB Atlas cluster.

### Running the Application

1. Start the Flask application:
    ```sh
    python app.py
    ```

2. Open your web browser and navigate to `http://127.0.0.1:5000` to access the survey form.

3. Fill in the survey form and submit the data.

### Data Processing and Visualization

1. After collecting the data, run the Jupyter notebook to process and visualize the data.

2. Navigate to the `notebooks/` directory:
    ```sh
    cd notebooks
    ```

3. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

4. Open the notebook and run the cells to load the data from the CSV file, process it, and generate the visualizations.

## Data


2. Install necessary packages on the EC2 instance (Python, Flask, etc.).
# License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

-
- pandas documentation: https://pandas.pydata.org/docs/
- matplotlib documentation: https://matplotlib.org/stable/contents.html
