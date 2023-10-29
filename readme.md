# README for Analyzing ZIKA Disease (SINAN Datasus)

## Overview

This project focuses on analyzing the ZIKA disease data from The Information System for Notifiable Diseases (SINAN) of DATASUS. SINAN is a crucial tool in Brazil's public health system, providing valuable data for understanding the spread and impact of notifiable diseases. This analysis specifically targets ZIKA virus data from the year 2016.

## Prerequisites

Before you can run this code, ensure that you have Python installed on your system. You can download Python from the official [Python website](https://www.python.org/). Additionally, you need to have Jupyter Notebook installed. You can install Jupyter Notebook by following the instructions provided [here](https://jupyter.org/install).

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required libraries using pip:

   ```bash
   pip install pysus pandas numpy plotly
   ```

## Usage

1. Open the Jupyter Notebook (`downloadZIKA.ipynb`) in your Jupyter environment.
2. Run the cells in sequence from top to bottom.

## Code Structure

- **Setting Up**: Installation of the required `pysus` library.
- **Fetching the Data**: Downloading the ZIKA disease data for the year 2016 using the `pysus` library.
- **Exploring the Data**: A brief exploration of the dataset, including checking the number of instances, viewing the columns, data types, and the first five rows of the dataset.
- **Data Cleaning**: Replacing empty strings with NaN values for better data handling.
- **Diving into the Cases of Zika**: Analyzing the 'DT_NOTIFIC' column, which indicates the date of notification.
- **Visualizing the Data**: Creating a histogram to visualize the distribution of ZIKA cases over time.

## Data Dictionary

The data dictionary, which provides detailed information on the dataset's variables, can be found [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vR8bNIx4IXRycpKcxqaPE1BGU9yPlwW_TuCn4lfZYE1fkM34gE8yRKosrcxZHV7jcZHS1kP11VHvg15/pub?gid=1507587706&single=true&output=pdf).

## Contributing

If you wish to contribute to this project, you can:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact

If you have any questions or feedback, please contact the project maintainers.

---

Happy Analyzing!
