
![Captura de pantalla 2023-06-26 a las 18 28 06](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/f9c3ce33-f987-4c74-b6e1-9afdb87a7399)



# DATA Cleaning & Visualization
Netflix csv from Kaggle.com  - Cleaning & Visualization


Main libraries: 

        
                1 - import numpy as np
                2 - import pandas as pd
                3 - import matplotlib.pyplot as plt
                4 - import seaborn as sns



First of all, we get the info about the CSV we are going to work with, and tidy the columns names up. Having 8789 entries and 10 columns in total.

![Captura de pantalla 2023-06-26 a las 18 50 42](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/32f8a809-9c29-4607-ae44-a768e2cc0ba1)



After checking column by column I found out that the Country's columns has 287 films that there is no DATA to see where it comes from, which it happens the same with the column of Directors, that we do not know who directed this films/ TV Shows..



![Captura de pantalla 2023-06-26 a las 18 57 31](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/eac263ee-dce6-4033-bd7a-0457a1fa79fb)


I wanted to check how much percetage there is with the Not Given DATA - which it looks a lot to me as follow:

Country only 3.27%
Directors has 29.44 (almost a third of the total Data) which is around -Total Number of Rows: 29853

![Captura de pantalla 2023-06-26 a las 19 05 05](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/d18beee9-ba11-434f-871b-b6a80aadfd1b)
![Captura de pantalla 2023-06-26 a las 19 10 57](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/79e9cf82-22e0-40ba-a76d-b058443a4707)



I decided after checking values, columns, duplicates and the rest, I decided that the Data Frame should be split between Movies & TV Shows

![Captura de pantalla 2023-06-26 a las 19 00 41](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/6b59ec26-11ce-4778-9c79-931c18721f81)



![Captura de pantalla 2023-06-27 a las 17 43 51](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/a2eb9b6a-e006-404b-ac45-84b0540dfe0a)

