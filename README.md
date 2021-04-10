# SARS-COV-2 spread, detection, and dynamics in a developing context

Data and replication files for "SARS-CoV-2 spread, detection, and dynamics in a megacity in Latin America" by  Rachid Laajaj, Camilo de los Rios, Ignacio Sarmiento-Barbieri, Danilo Aristizabal, Eduardo Behrentz, Raquel Bernal, Giancarlo Buitrago, Zulma Cucunubá, Fernando de la Hoz, Gabriela Delgado, Alejandro Gaviria, Luis Jorge Hernández, Leonardo León, Elkin Osorio, Andrea Ramírez Varela, Silvia Restrepo, Rodrigo Rodríguez, Martha Vives, Duncan Webb

# Abstract

In many developing countries, the COVID-19 pandemic has spread much faster and wider than the number of detected cases implies. By combining data from 59,770 RT-PCR tests on mostly asymptomatic individuals with administrative data on all detected cases, we capture the spread and dynamics of the COVID- 19 pandemic in Bogota ́ from June 2020 to February 2021. Our data provide unusually broad and detailed information on mostly asymptomatic adults in Bogota ́, allowing to describe various features of the pandemic that appear to be specific to a developing country context. We find that, by the end of Febru- ary 2021, slightly more than half of the population in Bogota ́ has been infected,  despite only a small fraction of this population being detected. In July 2020,  after four months of generalized quarantine that mitigated the pandemic with-  out curving it, the initial buildup of immunity contributed to the end of the  first wave. We also show that the share of the population infected by February  2021 varies widely by occupation, socio-economic stratum, and location. This  in turn, has affected the dynamics of the spread, with a first wave of infections  primarily driven by the lowest economic strata and jobs with a high exposi-  tion, compared to a second peak that affected the various groups more evenly. A better understanding of the spread and dynamics of the pandemic across 19 different groups provides valuable guidance for efficient targeting of health 20 policy measures and restrictions.



## Data files

- Datos_Salesforce_treated_feb19_clean.dta
- casos_SDS_poblaciones_23Jan2021.dta

## Software:

- The analysis is conducted using Stata-16 version 16.1 and R version 4.0.2 (2020-06-22) software

- All the code was run on a MacBookPro 2020 running macOS Big Sur Version 11.2.1

## Code files:
- 0_clean_covida_cats.R first clean the worker categories to be able to create the occupation wheights. # NOT NECESSARY
- _COVIDA_SALESFORCE_DATA_TREATMENT Feb 2021_CDR.do first clean of the original data as we receive it from the CoVIDA team # NOT NECESSARY
- _COVIDA_SALESFORCE_DATA_TREATMENT Feb 2021_CDR.do first clean of the original data as we receive it from the CoVIDA team # NOT NECESSARY
- 0_clean_sds.do first clean the HSB data as received from HSB.

- 1_fig1_CI.R generates figures 1a and 1b
- 1b_Iceberg_tables.R generates tables from figures 1a and 1b
- 2_strata_accum_CI_CoVIDA   generates figure 2 Unequal Exposure: by Strata from CoVIDA


Figures and tables are saved in the "views" folder. 



 
## Data dictionary

- Datos_Salesforce_treated_feb19_clean:

	- positive                                                  =1 if tested positive
	- test_day                                                  day that the test was administered
	

- casos_SDS_poblaciones_23Jan2021:

	- casos                                                                           cases
	

