# Somalia Budget Data 2018 - 2020

This repo contains the approved budget data released by Federal Government of Somalia's [Ministry of Finance](http://mof.gov.so/) for the fiscal year 2020. The data tables were extracted from the budget acts PDF file, cleaned, wrangled, and then convertd into tidy, machine readable format to ease access and analysis.

--------------------------------------------------------------------------------------

The csv file `somalia-fgs-budget-2020.csv` has the following structure:

Field | Definition
-------| --------------
`sector_code` | Refers to the unique numerical code for each of 4 major sectors of the gov't which is as follows - `100` - `Administration`, `200` - `Defense and Security`, `300` - `Economic Services`, `400` - `Social Services` and finally, `700` - `Special Projects`
`sector`| See above. Note: When computing the operating budget, exclude the special projects sector. 
`mda_code`| Unique numerical code for each ministry, department and agency reported.
`mda` | Ministries, Departments, and Agencies (MDA). There are 35 of these organizations that receieved budgetary allocation.
`sub_code` | Unique numerical code for each MDA i.e. `Parliament` is `102` and its Sub-sector the `Upper House` is `10203`
`sub_mda` | Names of the sub-sectors. See above for details.
`category_code` | Unique numerical code for each of the major eight expenditure categories. See below. 
`category` | Major budget categories consisting of eight divisions i.e. `grants`, `use of goods and services`, `compensation of employees`, `consumption of fixed capital`, `interests`, `subsidies`, `social benefits`, and `other expenses` 
`item_code` |  The specific numerical code for each budget line.
`item` | There are many levels, nearly 50, essentially the specific budget line.
`budget_type` | These are either - `adopted` or as enacted by parliament, `supplemental` or revised, and `actual`.
`amount` | Amount of money in USD dollars allocated for the corresponding budget line/item.
`year` | To be updated as more data for preceding years is included. Now it is from 2018 to 2020


### Feedback and Corrections
If you have suggestions to improve the file structure in order to facilitate wider access and use of these dataset by all interested stakeholders i.e. local journalists, researchers, and analysts or you have found an error please send me an email at mohamed@abdimalik.com  

Enjoy!!!