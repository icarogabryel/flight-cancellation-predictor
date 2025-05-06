# Datasets

In this directory, you will find the datasets used in the project.

## Raw Datasets

First, unzip the `weather.zip` and `flights.zip` files in the `raw` directory.

This directory contains the original datasets of flights and weather that was used to create the merged datasets. These datasets have not been modified or cleaned, and they are in their original format.

The flights dataset was obtained from ANAC (Agência Nacional de Aviação Civil) and contains information about flights in Brazil of 2024, including flight numbers, departure and arrival airports, and flight times. the data set can be found here: [ANAC](https://siros.anac.gov.br/siros/registros/diversos/vra/2024/).

The weather dataset was obtained from INMET (Instituto Nacional de Meteorologia) and contains information about weather conditions in Brazil, including temperature, humidity, and precipitation. The data set can be found here: [INMET](https://portal.inmet.gov.br/dadoshistoricos).

## Processed Datasets

The `processed` directory contains the merged datasets that was created by combining the flights and weather datasets and with additional features such as the day of the week and holidays. This dataset has been cleaned and preprocessed to remove any missing or irrelevant data.
