# AQI to Cigarette Equivalent Calculator

This web-based tool calculates the equivalent number of cigarettes smoked based on the Air Quality Index (AQI) and the duration of exposure (in hours). It provides a simple and interactive way to understand the potential health impacts of poor air quality by comparing it to cigarette smoking.

## Features
- Converts AQI to PM2.5 concentration using the EPA formula.
- Calculates the equivalent number of cigarettes smoked based on the exposure time.
- Displays the AQI category (Good, Moderate, Unhealthy, etc.) and its associated health risks.
- Fully responsive and user-friendly design.

## How it Works
- The tool takes the AQI value and exposure duration (in hours) as inputs.
- It then calculates the PM2.5 concentration based on the AQI using the EPA’s formula.
- Using the assumption that 22 µg/m³ of PM2.5 over 24 hours is equivalent to smoking one cigarette, the tool calculates the cigarette equivalent.
- The results show the equivalent number of cigarettes smoked and the AQI category based on the input.

## AQI Categories
The AQI is divided into the following categories, which correspond to different levels of health concern:
- **Good (0-50)**: Air quality is considered satisfactory.
- **Moderate (51-100)**: Air quality is acceptable; however, some pollutants may be a concern for sensitive individuals.
- **Unhealthy for Sensitive Groups (101-150)**: People with respiratory or heart conditions are at risk.
- **Unhealthy (151-200)**: Everyone may begin to experience health effects, and members of sensitive groups may experience more serious effects.
- **Very Unhealthy (201-300)**: Health alert; everyone may experience more serious health effects.
- **Hazardous (301 and above)**: Health warnings of emergency conditions; the entire population is more likely to be affected.

## How to Use
1. Enter the AQI value in the input box (e.g., 200).
2. Enter the exposure duration in hours (e.g., 24).
3. Click the "Calculate" button to see the equivalent number of cigarettes smoked and the AQI category.
4. The result will show the number of cigarettes smoked during the exposure, along with the AQI category and associated colour-coded risk level.

## Installation

To run the tool locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AQI-to-Cigarette-Calculator.git
2. Navigate to the project folder:
   ```bash
   cd AQI-to-Cigarette-Calculator
   
3. Open the `index.html` file in your web browser.

## Contributing

Feel free to fork this repository and contribute by submitting pull requests. If you have any suggestions or improvements, please open an issue.

## License

This project is open source and available under the MIT License. See the [LICENSE](https://github.com/bhavishyasingla1/AQI-to-Cigarette-calculator/blob/main/LICENSE) file for more details.

## Acknowledgements

1. This tool is inspired by [Jasminedevv's AQI to Cigarette Calculator](https://jasminedevv.github.io/AQI2cigarettes/).
2. The calculation uses the EPA’s formula to convert AQI to PM2.5 concentration.

## Contact

For questions or feedback, you can reach me on [GitHub](https://github.com/bhavishyasingla1).





