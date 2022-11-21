
This repository has files containing details of structural fires caused by exploding e-bike batteries since Jan, 31, 2022. 
THE CITY analyzed this data and was used in writing the story – <a href="https://www.thecity.nyc/2022/11/21/23468257/ebikes-fires-lithium-ion-batteries-delivery-workers">"Where and Why E-Bikes Catch Fire in NYC"</a>. 

In response to a FOIL request, THE CITY's investigative reporter Greg Smith received two PDF files from the New York City Fire Department. The files provided details about 294 structural fires caused by exploding lithium-ion batteries between Jan. 1, 2021 and Nov. 15, 2022. The details included the date, time, address, borough and ZIP code of each of the e-bike fires recorded in the 23 months.

Lithium Addresses 2021.pdf lists 2021 e-bike fires
Lithium Addresses 2022.pdf lists year-to-date 2022 e-bike fires

THE CITY converted these PDFs to CSV which were then combined into a single file. We used geocodio.io to generate coordinates for each address. The conversions with less than 100% accuracy were manually changed. 

We plotted these incidents using the latitude and longitude attributes to create a density map. 


