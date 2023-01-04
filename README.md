# CENG313_TeamGolduck

Team Golduck Final Project

All of the datasets can be found in our github repository

https://github.com/melihacil/CENG313_TeamGolduck


Datasets

Development Index Dataset

https://www.kaggle.com/code/stieranka/predicting-gdp-world-countries/data

EU Inflation Dataset

https://www.kaggle.com/datasets/hgultekin/hicp-inflation-rate

GDP Dataset

https://www.kaggle.com/datasets/nitishabharathi/gdp-per-capita-all-countries



World Bank Datasets


These datasets can be obtained easily by removing the commentations on our codes  

#servicesData = wb.data.DataFrame('BM.GSR.TOTL.CD', economy= wb.region.members('ECS'),time = range(2000,2019),numericTimeKeys= True,labels= True)  
#servicesData.to_csv('WorldBankSets/servicesData.csv')  
#techData = wb.data.DataFrame('TX.VAL.OTHR.ZS.WT', economy= wb.region.members('ECS'),time = range(2000,2019),numericTimeKeys= True,labels= True)  
#techData.to_csv('WorldBankSets/techData.csv')  
#commercialData = wb.data.DataFrame('TX.VAL.SERV.CD.WT', economy= wb.region.members('ECS'), time = range(2000,2019),numericTimeKeys= True,labels= True)  
#commercialData.to_csv('WorldBankSets/commercialData.csv')
#inflationData = wb.data.DataFrame('FP.CPI.TOTL.ZG', time = range(2000,2019),numericTimeKeys= True,labels= True)  
#inflationData.to_csv('WorldBankSets/inflationData.csv')
#electricityData = wb.data.DataFrame('EG.ELC.ACCS.ZS', time = range(2000,2019),numericTimeKeys= True,labels= True)  
#electricityData.to_csv('WorldBankSets/electricityData.csv')  


World Bank Dataset Informations 

BM.GSR.TOTL.CD	Imports of goods, services and primary income (BoP, current US$)  
BM.GSR.TRAN.ZS	Transport services (% of service imports, BoP)  
BX.GRT.TECH.CD.WD	Technical cooperation grants (BoP, current US$)  
TX.VAL.OTHR.ZS.WT	Computer, communications and other services (% of commercial service exports)  
TX.VAL.SERV.CD.WT	Commercial service exports (current US$)  
TX.VAL.TECH.CD	High-technology exports (current US$)  
EG.ELC.ACCS.ZS	Access to electricity (% of population)  
FP.CPI.TOTL.ZG    inflation  