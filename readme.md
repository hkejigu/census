##ABOUT CENSUS DATA


1. Zimbabwe is divided into **PROVINCES**, **DISTRICTS** and **WARDS** for administrative purposes. See ([this repository](https://github.com/zimgeospatial/admin_boundaries)), thus consequently enumeration areas are similarly defined.

2. Census data here can easily be appended to spatial/ map data via the use of [P-Codes](https://github.com/zimgeospatial/admin_boundaries) associated with the data.  

---
###1. Wards [ ward_population.csv]

####Summary
- Has population figures as per the 2012 National Census.

####Field Definitions:

| Field Name        | Explanation          | 
| ------------- |-------------| 
| wardpc      | P-Code for the ward. (Place Code) |
| wardname     | The name of the ward which is actually a number. |
| province      | The name of the province.      | 
| district      | The name of the district.      | 
| alt_name      | Altenative name for the district. |
| districtpc      | P-Code for the district. (Place Code) |
| pop_2012      | Total population for that ward in 2012. |
| f_pop_2012      | Total **Female** population for that ward in 2012. |
| m_pop_2012      | Total **Male** population for that ward in 2012.  |
| households      | Total number of households in that ward.|

---
###2. PROVINCE [ province_population.csv ]

####Summary
- Contains provincial population values for the years 1982, 1992, 2002 and 2012.

####Field Definitions:

| Field Name    | Explanation                                      |
| ------------- | -------------                                    |
| provincepc    | P-Code for the Province. (Place Code)            |
| province      | Name of the province.                |
| pop_1982      | Total population for that province in 1982. |
| pop_1992      | Total population for that province in 1992. |
| pop_2002      | Total population for that province in 2002. |
| pop_2012      | Total population for that province in 2012. |
| m_pop_2012      | Total **Male** population for that ward in 2012.  |
| f_pop_2012      | Total **Female** population for that ward in 2012. |

---
