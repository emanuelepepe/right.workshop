# Workshop at right.: Candidate Emanuele Pepe


#### ERD of SQL-Database
![ERD_emissions_workshop_EPepe](https://user-images.githubusercontent.com/17638985/120300035-dacdc480-c2cb-11eb-9738-6b095570893f.png)

#### SQL quiry to retrieve the data from database as in ERD:

SELECT revenue,emission,emp_count,sector,country

&nbsp;&nbsp;FROM companies AS Tcom

&nbsp;&nbsp;&nbsp;&nbsp;JOIN countries AS Tcoun

&nbsp;&nbsp;&nbsp;&nbsp;ON Tcom.country_id = Tcoun.country_id

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;JOIN sectors AS Tsec

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ON Tcom.sector_id = Tsec.sector_id
