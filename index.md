# PRIME - Portuguese Regional Ionosphere Model

## Project Summary
The main goal of the exploratory PRIME (Portuguese Regional Ionosphere ModEl) project is to develop a prototype for a regional model to simulate and forecast variations of the ionospheric parameters such as the total electron content in relation to space weather events. Space Weather (SW) is an umbrella term for phenomena observed in the near-Earth space (magnetosphere), in the Earth's atmosphere (ionosphere, and middle and lower atmosphere) and even in the upper lithosphere that are related to variations of the solar activity (solar flares, coronal mass ejections, etc.) and the interplanetary medium (e.g., cosmic ray flux).

SW is one of the main drivers of ionospheric disturbances which, in turn, can drastically affect the quality of the signal between a ground-based device and the GNSS (global navigation satellite systems) satellites. Engineering solutions can overcome some problems of signal propagation. Yet, forecasting and early warning for potentially dangerous SW events are also essential for the improvement of the quality of the GNSS-based services, such as operations of the unmanned air-born, floating and land vehicles for surveys and investigations of hard-to-reach objects and locations, navigation of newly developed autonomous vehicle to transport goods and passengers, GNSS-assisted landing procedures for commercial aviation, GNSS positioning during rescue operations, etc.

The GNSS receivers themselves are a reliable source of ionospheric data. Networks of GNSS receivers nowadays densely cover all heavily populated areas, Continental Portugal included. The data from GNSS receivers can be utilized to estimate such widely used ionospheric parameters as the total electron content (TEC) and scintillation indices (S4, sigma_phi or ROTI - rate of TEC index).

The forecasts of the ionospheric parameters are based on the understanding of the ionosphere reaction to different forcings. Empirical (based on the observational data and statistical analysis of such data) models for ionospheric response to external forcings (solar flares, geomagnetic storms and other events as sudden stratospheric warmings or solar eclipses) are being developed by different research groups for their countries. To the moment no such model for Portugal exists.

In our project PRIME we propose to develop a prototype for an empirical model to forecast TEC variations for Portugal in response to the changes of the space weather conditions. As input ionospheric data for the models the GNSS-derived TEC will be used. The team members of the PRIME project have already tested a simplistic empirical model able to forecast TEC for the Continental Portugal using space weather parameters as predictors [A]. In this project we plan to develop a sophisticated model that is based on neural networks (NN). NN will be trained on the TEC observations and on a set of space weather parameters to forecast TEC variations for 1-2 days forwards. Later, during a further development project, this prototype will be adjusted and calibrated to be used for the entire Portuguese region.

The Continental Portugal region is well covered by GNSS receivers, and variations of TEC for this region are studied quite well, both by other researchers and the team members of the PRIME project. On the contrary, the knowledge of variations of TEC for the island regions (Azores and Madeira) is still insufficient due to the lack of the observational ionospheric data. The second goal of the PRIME project is to fill this gap, and to use the newly acquired data to build a dedicated TEC model for the Islands. 

The PRIME project will be developed in the new node of IA (Institute for Astrophysics and Space Science) at UC. It will contribute to the promotion and development of research infrastructure in Portugal and training of human resources (a master and PhD students), and researchers with renowned reputation from other countries will work with the PRIME team as consultants. The project will also promote the knowledge transfer between R&D centers and business.

## Team
Anna Morozova (PI)
Teresa Barata (co-PI)
Ricardo Gafeira
Sara Carvalho

### Institution
Institute for Astrophysics and Space Science, University of Coimbra, Coimbra, Portugal

### Funding
The project is funded by the Fundação para a Ciência e a Tecnologia (FCT), Portugal:  EXPL/CTA-MET/0677/2021
