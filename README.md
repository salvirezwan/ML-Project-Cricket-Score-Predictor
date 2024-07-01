# Cricket Score Predictor

This is a Machine Learning Project that predicts the cricket score based on input parameters such as batting team, bowling team, city, current score, overs bowled, wickets out, and runs in the last 5 overs.

## Features

- Predicts the final score of a cricket match based on current match conditions.
- Uses Bootstrap for responsive design and styling.
- Validates user input to ensure meaningful predictions.

## Technologies Used

- HTML
- CSS (Bootstrap)
- JavaScript (jQuery)
- Flask (for backend logic)
- Python (for prediction logic)

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/cricket-score-predictor.git
   cd cricket-score-predictor

## Create a virtual environment and activate it:

 ```bash
python -m venv venv
source venv/bin/activate

## install required packages:
flask,
sci-kit learn,
pandas,
etc.

## Customization
To add more teams or cities, update the dropdown options in the index.html file.
To change the default teams or city, modify the JavaScript logic in the index.html file to set the desired default values.
To adjust the prediction logic, update the backend logic in app.py.


## Usage
Select the batting team, bowling team, and city from the dropdown menus.
Enter the current score, overs bowled, wickets out, and runs scored in the last 5 overs.
Click the "Predict Score" button.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any features, bug fixes, or improvements.
