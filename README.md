# Workshop at right.: Candidate Emanuele Pepe


#### SQL quiry to retrieve the data from database as in ERD:

SELECT revenue,emission,emp_count,sector,country

&nbsp;&nbsp;FROM companies AS Tcom

&nbsp;&nbsp;&nbsp;&nbsp;JOIN countries AS Tcoun

&nbsp;&nbsp;&nbsp;&nbsp;ON Tcom.country_id = Tcoun.country_id

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;JOIN sectors AS Tsec

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ON Tcom.sector_id = Tsec.sector_id
