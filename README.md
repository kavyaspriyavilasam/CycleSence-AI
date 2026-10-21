 CycleSense AI — Menstrual Cycle Analytics Dashboard
📌 Project Overview

CycleSense AI is a Python-based menstrual cycle tracking and analytics dashboard developed using Google Colab and Gradio. It analyzes recorded period dates, summarizes cycle history, estimates the next period, and demonstrates basic statistical prediction evaluation.

This project was built to practise Python programming, data analysis, visualization, and prediction evaluation.

✨ Features

- 📅 Period start and end date inputs
- 🔮 Estimated next-period date and date range
- 📊 Cycle history and cycle-length analytics
- 🗓️ Estimated period calendar
- 📈 Cycle-length visualization
- 🧪 Basic prediction evaluation using Mean Absolute Error (MAE)
- 🔍 Actual-versus-predicted cycle-length chart
- 📥 CSV export of cycle history

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Gradio
- Google Colab

⚙️ How It Works

1. Enter historical period start dates and, optionally, matching end dates.
2. The application calculates intervals between consecutive start dates.
3. It summarizes historical cycle lengths and displays a cycle history table.
4. It estimates the next period using a median-based statistical heuristic.
5. It visualizes cycle patterns and provides a CSV download.
6. A separate evaluation function compares historical predictions with observed cycle lengths using MAE.

📈 Prediction Evaluation

The project includes a basic walk-forward evaluation that compares a median-based prediction method with a mean-based baseline.

Mean Absolute Error (MAE) measures the average absolute difference between predicted and observed cycle lengths. Lower MAE indicates smaller errors on the evaluated examples.

The evaluation is educational and uses limited sample data. It does not establish clinical accuracy.

🚀 How to Run

1. Open the ".ipynb" notebook in Google Colab.
2. Run the installation cell to install the required libraries.
3. Run the import and function-definition cells in order.
4. Run the Gradio interface cell.
5. Open the generated application link to test the dashboard.

🔮 Future Improvements

- Evaluate the method on larger, suitable datasets.
- Improve input validation and automated testing.
- Compare additional forecasting baselines.
- Improve dashboard design and reporting.
- Explore machine-learning approaches when sufficient data is available.

⚠️ Limitations and Disclaimer

CycleSense AI is an educational project, not a medically validated prediction tool. Estimates may be inaccurate, especially when cycles are irregular or historical data is limited. The application must not be used for diagnosis or contraception decisions.

The current prediction approach is a statistical heuristic; it is not a trained machine-learning model. Do not enter sensitive personal health information into a public demo.

👩‍💻 Project Purpose

This project demonstrates practical learning in Python, data analytics, data visualization, and basic model evaluation for an AI and Data Analytics portfolio.
