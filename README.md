# Passport Index Dataset

The dataset in this repository is a collection of information from the Passport Index website, which is a platform that ranks passports from around the world based on their power and the access they provide to their holders to enter different countries. This dataset here is updated monthly to ensure that the information provided is current and accurate.

![Passport](world-flags.png)

## Description

The dataset collected from the Passport Power Index website includes a wide range of information related to the visa requirements for different countries. It includes details on the visa-free entry, visa on arrival, and eVisa policies for each country.

This data can be analyzed to gain insights into the countries with the most powerful passports, as well as those with more restricted visa policies. Researchers can also use this data to explore the relationship between a country's economic, political, and social factors and its visa policies.

The scraper retrieves the following data from the website:

- Country name
- Visa-free score
- Visa on arrival score
- Electronic travel authorization (ETA) score
- Visa required score Mobility score

The data is saved in CSV file that can be used for further analysis or visualizations.


## Output
The data is saved in an excel file named passport-power-{date}.xlsx in the same directory as the project repo. Similarly, previous data history can be found in folder named history inside project repo. This excel file contains two sheets of information related to visa policies.

- Sheet 1 provides comprehensive information on visa requirements for different origin-destination pairs
- Sheet 2 includes detailed visa information for each country, including the number of countries offering visa-free access, visa-on-arrival, electronic travel authorization (ETA), and visa-required status.

Additionally, Sheet 2 also provides the mobility score which represents the total number of countries that can be conveniently reached using a specific passport. This score is computed by taking into account the total number of countries that grant visa-free entry, visa-on-arrival, electronic travel authorization (eTA), and eVisa issued within three days.


## MIT License

Passport Index is completely free of charge and has been constructed using information that is readily available to the public. The content featured on this platform has been generously contributed by devoted supporters as well as various governmental organizations from all corners of the globe. You are more than welcome to utilize the dataset available on Passport Index in accordance with the MIT license.

Source: https://www.passportindex.org
