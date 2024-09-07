# caribbean-vaccination
Caribbean Vaccination Coverage Shiny App
This Shiny app visualizes the vaccination coverage rates in various Caribbean countries over time. Users can explore data for different vaccines or select all vaccines for a specific country. The app is built using the R Shiny framework and the tidyverse suite for data manipulation and visualization. Visit the live version: https://stepminer.shinyapps.io/caribbean_vaccination/

Features
Select from 16 Caribbean countries, including Haiti, Cuba, Dominican Republic, Jamaica, etc.
Visualize immunization coverage for individual vaccines or all vaccines over time.
Vaccines covered include BCG, HepB3, Hib3, IPV1, MCV1, PCV3, Pol3, RCV1, RotaC, YFV, and DTP3.
Data is represented as line and point charts for easy comparison.
Screenshot
(Include a screenshot of your app here to give users a preview of its interface.)

Data
The app uses vaccination data from a CSV file (vaccine.csv). The columns of the data include:

Entity: The country or entity name.
Year: Year of immunization coverage.
Vaccines: Various columns representing the percentage of one-year-olds immunized for specific vaccines.
Vaccines Covered:
BCG
HepB3
Hib3
IPV1
MCV1
PCV3
Pol3
RCV1
RotaC
YFV
DTP3
Data Example
Entity	Year	BCG (%)	HepB3 (%)	Hib3 (%)	...
Haiti	2020	85	70	65	...
Jamaica	2020	90	80	75	...
Prerequisites
To run the app locally, you will need the following installed on your machine:

R (version 4.0 or higher)
RStudio (optional but recommended)
The following R packages:
shiny
tidyverse
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/vaccination-app.git
Navigate to the app directory:

bash
Copy code
cd vaccination-app
Install the required R packages:

In RStudio or an R terminal, run the following:

r
Copy code
install.packages(c("shiny", "tidyverse"))
Run the Shiny app:

r
Copy code
shiny::runApp()
Usage
Select Country: Choose one of the 16 Caribbean countries from the dropdown menu to view vaccination data.
Select Vaccine: You can select a specific vaccine to visualize, or choose "All" to view data for all vaccines at once.
The plot will dynamically update based on the selections, displaying a time series of vaccination coverage.
File Structure
bash
Copy code
├── app.R                # Main Shiny app script
├── vaccine.csv          # Vaccination data (input file)
├── README.md            # This README file
└── ...
Contributing
Feel free to submit issues or pull requests for any enhancements or bug fixes. Contributions are welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Data source: WHO; UNICEF (2022) – Learn more about this data

OurWorldInData.org/vaccination | CC BY.
Inspiration: Developed to provide insights into vaccination rates in the Caribbean region.
 
