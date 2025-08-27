# Netflix Analysis

This project provides an exploratory data analysis (EDA) of a Netflix dataset using Python, Pandas, and visualization libraries. The analysis was performed in a Jupyter Notebook (Google Colab).

## Dataset

The dataset used includes information about Netflix shows and movies such as:
- Show ID
- Type (Movie/TV Show)
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genres (listed_in)
- Description

The dataset was sourced from:  
https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/000/940/original/netflix.csv

## Main Steps in the Notebook

1. **Importing Libraries**:  
   Standard Python libraries for data analysis and visualization, such as `pandas`, `numpy`, `matplotlib`, and `seaborn`, are imported.

2. **Data Loading**:  
   The dataset is downloaded and loaded into a DataFrame.

3. **Initial Data Exploration**:  
   - Display first 5 rows (`head`)
   - DataFrame info and statistics (`info`, `describe`)
   - Data shape (rows and columns)
   - Check and analyze missing values

4. **Insights**:  
   - The `director` column has about 30% missing values.
   - Other columns have relatively few missing values.

5. **Further Analysis & Visualization**:  
   *(Add details here if you add more analysis, e.g., popular genres, trends over years, etc.)*

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/arcvrsh/Netflix-Analysis.git
   cd Netflix-Analysis
   ```

2. Open `Netflix.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.

3. Run the notebook to see the analysis.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

If running locally, you can install the requirements with:
```bash
pip install pandas numpy matplotlib seaborn
```

## Notes

- The notebook includes code to download the dataset automatically.
- For best experience, run this in Google Colab or a Jupyter environment.

## License

This project is for educational and analysis purposes.
