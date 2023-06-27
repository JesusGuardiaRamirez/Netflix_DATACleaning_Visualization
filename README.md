
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

![Captura de pantalla 2023-06-27 a las 17 44 52](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/20db4411-bac1-48e3-a72a-3b66cb3cc932)


![Captura de pantalla 2023-06-27 a las 17 54 37](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/027bf372-026e-4d2e-b7d6-49045b84774a)



### VISUALIZATION

Top of 10 Countries that has produced more TV SHOWS:

        United States     845
        Pakistan          350
        United Kingdom    251
        Japan             172
        South Korea       165
        Canada             84
        India              81
        Taiwan             71
        France             65
        Australia          53



![Captura de pantalla 2023-06-27 a las 17 46 08](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/2ba98609-aec3-470a-9e91-4c53e963bdbf)


Top of 10 Countries that has produced more MOVIES:


        United States     2395
        India              976
        United Kingdom     387
        Canada             187
        France             148
        Spain              129
        Egypt              109
        Nigeria             96
        Mexico              90
        Japan               87


 ![Captura de pantalla 2023-06-27 a las 17 49 38](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/6a4db95a-298f-4ede-859c-eb730951fdb6)


Top of 5 Directors that has produced more MOVIES:

        Rajiv Chilaka             19
        Raúl Campos, Jan Suter    18
        Suhas Kadav               16
        Marcus Raboy              15
        Jay Karas                 14





 ![Captura de pantalla 2023-06-27 a las 17 52 11](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/bfe4d0f9-ab49-477c-bec9-721d275700b7)


Top of 5 Directors that has produced more TV SHOWS:


        Alastair Fothergill             14
        Mark Thornton, Todd Kauffman     5
        Stan Lathan                      3
        Iginio Straffi                   2
        Rob Seidenglanz                  2


 ![Captura de pantalla 2023-06-27 a las 17 53 24](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/e26dc66b-e7f8-45ce-bbb1-57ced7f5fbf1)




 Top 10 Categories including TV Shows and Movies:


 ![Captura de pantalla 2023-06-27 a las 17 56 00](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/3cad07ff-05ec-4199-bd9c-e0fb73b51626)


Most Shows / Movies where released around 2020


![Captura de pantalla 2023-06-27 a las 17 57 29](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/18e1b344-1551-4bdb-acf0-31f4771298d0)



And lastly, top 15 countries that has reproduced the most, having USA on the head. 


![Captura de pantalla 2023-06-27 a las 17 58 16](https://github.com/JesusGuardiaRamirez/Netflix_DATACleaning_Visualization/assets/125477881/27ce1d57-10de-45cd-90ea-d55ef9b9b59a)
