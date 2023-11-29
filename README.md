# Traffic Accidents in the Autonomous City of Buenos Aires, Argentina, 2016-2021.
__Amelia Herrera Briceño__
* melinnicri@gmail.com
* September 2023.


<p align="center"><img src="https://github.com/melinnicri/Traffic_accids/blob/main/images/Accidentes.jpg"></p>

Data analyst role work about traffic accidents that occurred between the years 2016-2021, in the Autonomous City of Buenos Aires, Argentina (CABA).
Traffic accidents are one of the main causes of death and injuries in the city. According to the Buenos Aires government, the factors that contribute to accidents are non-compliance with traffic laws, excessive speed, failure to respect traffic signs, failure to use a seat belt or headrest, and driving while tired. Furthermore, the means of transportation most involved in accidents are motorcycles, followed by cars and buses. Traffic accidents generate a high social and economic cost, as well as a negative impact on people's quality of life.

Databases are provided with information about homicides and victims (data from official Argentine websites).
An ETL and EDA are carried out, respectively, using Jupyter notebook, Pandas library, and its final presentation in PowerBI.

Requested KPIs:
* 1)
Reduce by 10% the homicide rate in road accidents in the last six months, in CABA, compared to the homicide rate in road accidents in the previous semester (semester year 2021-2020). We define the homicide rate in road accidents as the number of fatal victims in traffic accidents per 100,000 inhabitants in a geographic area during a specific period of time. Its formula is: (Number of homicides in road accidents / Total population) * 100,000.

* 2)
Reduce the number of fatal motorcyclist accidents by 7% in the last year, in CABA, compared to the previous year (year 2021-2020). We define the number of fatal accidents involving motorcyclists in road accidents as the absolute number of fatal accidents in which victims traveling by motorcycle were involved in a certain time period. Its formula to measure the evolution of fatal accidents with motorcycle victims is: (Number of fatal accidents with motorcycle victims in the previous year - Number of fatal accidents with motorcycle victims in the current year) / (Number of fatal accidents with motorcycle victims in the previous year) * 100.

* 3)
With data on the number of victims per commune, the communes with the most accidents are taken to calculate the mortality rate from road accidents. To do this, you must divide the number of fatalities by the number of inhabitants of each commune and multiply by 100,000. This results in the mortality rate per 100,000 inhabitants, which is a standardized indicator that allows comparisons between communes.

# The 15 communes of the Autonomous City of Buenos Aires:
- COMMUNE 1: Retiro, San Nicolás, Puerto Madero, San Telmo, Montserrat and Constitución.
- COMMUNE 2: Recoleta.
- COMMUNE 3: Balvanera and San Cristóbal.
- COMMUNE 4: La Boca, Barracas, Parque Patricios and Nueva Pompeya.
- COMMUNE 5: Almagro and Boedo.
- COMMUNE 6: Caballito.
- COMMUNE 7: Flores and Chacabuco Park.
- COMMUNE 8: Villa Soldati, Villa Riachuelo and Villa Lugano.
- COMMUNE 9: Liniers, Mataderos and Parque Avellaneda.
-COMMUNE 10: Villa Real, Monte Castro, Versalles, Floresta, Vélez Sarsfield and Villa Luro.
- COMMUNE 11: Villa General Miter, Villa Devoto, Villa del Parque and Villa Santa Rita.
- COMMUNE 12: Coghlan, Saavedra, Villa Urquiza and Villa Pueyrredón.
- COMMUNE 13: Núñez, Belgrano and Colegiales.
- COMMUNE 14: Palermo.
- COMMUNE 15: Chacarita, Villa Crespo, La Paternal, Villa Ortúzar, Agronomía and Parque Chas.

# Files:
- "Accidentes"
- "Bases_datos"

# Conclusions:
According to the results obtained in PowerBI, we can conclude that:

- Between the years 2016 and 2021, in CABA, traffic accidents tended to decrease, partly due to the pandemic (mobilization restriction) and increased again after this confinement.

- It is striking that in the mornings there were more accidents (7 hours), they are supposed to be “rested”.

- The mortality rate per 100,000 inhabitants between 2016 and 2021 is 23.4 (717 deceased victims).

- The most frequent type of traffic accident is pedestrians being run over by buses and motorcycles colliding with cars, where the number of deaths is also high.

- The ages of the deceased victims are most frequently in the range of 20-29 years and the majority are male.

- The top 5 (over 60 fatalities) by CABA communes are Comune 1 (Retiro, San Nicolás, Puerto Madero, San Telmo, Montserrat and Constitución); Commune 4 (La Boca, Barracas, Parque Patricios and Nueva Pompeya); Commune 7 (Flores and Parque Chacabuco), Commune 8 (Villa Soldati, Villa Riachuelo and Villa Lugano), Commune 9 (Liniers, Mataderos and Parque Avellaneda).

# As one of the KPIs:

* 1) In the first six months (January-June) of 2020-2021, there is an increase of 77.23% in the mortality rate per 100,000 inhabitants. In the semiannual section (July-December) there was a reduction of 16.09%. Therefore, the expected 10% reduction in July-December is met.

* 2) Regarding motorcycle deaths, it increased by 29.72% from one year to the next (2020-2021), so it was not possible to reduce it by 7% as expected.

* 3) Regarding the mortality rate per 100,000 inhabitants with the top 5 are the communes: Comune 1 (0.33), Comune 4 (0.49), Comune 7 (0.42), Comune 8 (0.55 ), Comune 9 (0.82), between 2016 and 2021.

Panel published in: "Accidentes" file.



<p align="center"><img src="https://github.com/melinnicri/Traffic_accids/blob/main/images/print01.png"></p>

## ..._@v
