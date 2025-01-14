# Simple Linear Regression from Scratch

## Project Overview
This project demonstrates the implementation of **Simple Linear Regression** using Python. Simple Linear Regression is a statistical method that allows us to summarize and study relationships between two continuous variables.

## Key Features
- Data preprocessing and visualization
- Model training using Gradient Descent
- Mean Squared Error (MSE) calculation
- Visualization of regression results

## Technologies Used
- Python
- Pandas
- Matplotlib (for data visualization)

## Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd SimpleLinearRegression
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook SimpleLinearRegression.ipynb
   ```
2. Run the cells step-by-step to:
   - Load and visualize the dataset (`Father_Son.csv`)
   - Calculate the Mean Squared Error (MSE)
   - Train the model using Gradient Descent
   - Visualize the fitted regression line

## Workflow Breakdown
### 1. Data Visualization
- Load the dataset and plot the relationship between father's and son's heights.

### 2. Mean Squared Error (MSE)
- A function calculates the MSE to measure the model's prediction error.

### 3. Gradient Descent
- An optimization technique to minimize the MSE by updating model parameters (slope and intercept).

### 4. Model Training
- Iteratively adjusts the slope (`m`) and intercept (`b`) using Gradient Descent for a defined number of epochs.

### 5. Results Visualization
- Plots the regression line over the data to visualize model performance.

## Project Structure
```
SimpleLinearRegression/
├── SimpleLinearRegression.ipynb  # Main notebook file
├── data/                         # Dataset (Pearson.csv)
├── images/                       # Plots and images generated
├── requirements.txt              # List of dependencies
└── README.md                     # Project documentation
```

## Results
The model outputs a regression line fitted to the data, along with evaluation metrics such as:
- Mean Squared Error (MSE)

## Contributing
Feel free to fork this repository and submit pull requests to enhance the project.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or feedback, please reach out to:
- Kaustubh Nadkar
- Email: kaustubhnakdar010@gmail.com

