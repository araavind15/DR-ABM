# DR-ABM
An agent based model to simulate consumer enrollment in residential demand response based on both financial and social factors of consumers

First run the HEMS-upload.ipynb file to obtain all the required files for HEMS optimization of the household. The data file called 2019_data_upload.xlsx contains the dataset of spot price, spot emission, PV generation and Temperature in Helsinki. The spot price is obtained from Nordpool, the emission data is obtained from Fingrid, the PV generation is obtained from PV GIS developed by Suri et al. (2008) (https://publications.jrc.ec.europa.eu/repository/handle/JRC43229). 

The process of HEMS is as follows:

![alt text](HEMS-flow.png "HEMS operation")


The process of ABM is as follows:
![alt text](ABM-flowpng "ABM workflow")


Detailed explanation of this work is provided in https://www.sciencedirect.com/science/article/pii/S0306261924013710#b56
If you decide to use this, please use the following citation: Sridhar, A., Honkapuro, S., Ruiz, F., Stoklasa, J., Annala, S. and Wolff, A., 2024. Residential consumer enrollment in demand response: An agent based approach. Applied Energy, 374, p.123988.

