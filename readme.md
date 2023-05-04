# Garmin Sleep Analysis

This project focuses on analyzing sleep data obtained from Garmin devices to gain insights into sleep patterns and habits. Garmin is a popular brand that produces wearable devices, such as smartwatches, which can track various health metrics, including sleep data. This sleep data consists of information like sleep start time, sleep end time, sleep duration, sleep stages (deep, light, and REM), and sleep scores.

## Getting Started

To begin analyzing your own Garmin sleep data, follow these steps:

1. **Export your Garmin sleep data**: Check out https://support.garmin.com/en-US/?faq=W1TvTPW8JZ6LfJSfK512Q8

2. **Organize your data**: Create a folder named `data` in your project directory, and store all the downloaded JSON files in this folder.

3. **Set up your environment**: Install the required Python libraries by running `pip install pandas seaborn matplotlib numpy`.

4. **Analyze your sleep data**: Run the provided Jupyter Notebook to load, clean, and analyze your sleep data. The notebook contains various visualizations, such as sleep score distribution, sleep start and end times, sleep duration, and correlations between different sleep metrics.

## Key Features

The Garmin Sleep Analysis project offers the following key features:

- **Data Import**: The project efficiently imports sleep data from multiple JSON files and combines them into a single DataFrame for further analysis.

- **Data Cleaning**: The project cleans and preprocesses the data by converting date columns to datetime objects, filtering rows with valid time information, and removing unnecessary columns.

- **Visualizations**: The project provides several visualizations to help you explore and understand your sleep data, including:
  - Sleep scores feedback distribution
  - Sleep start and end time distribution
  - Sleep duration distribution
  - Ratio of positive and negative feedback
  - Correlations between different sleep metrics

- **Insights**: The project helps you gain insights into your sleep patterns and habits, such as:
  - Average sleep duration
  - Sleep duration on weekdays vs. weekends
  - Sleep start and end times on weekdays vs. weekends
  - Seasonal variations in sleep duration

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions for improvements or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
