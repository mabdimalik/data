# Somalia Aid Flows 2016 - 2018

The data contained in this repo was initially downloaded from Somalia's Aid Coordination Unit's [ACU](https://twitter.com/ACUSomalia) now defunct [website](http://somaliaaidflows.so) as JSON files. This first version consists of tidy dataset covering 770 aid and development projects funded by Somalia's donors from 2016 to 2018. Calling on all local researchers, analysts, journalists to download and explore the data. Let me know what you find. Thank you!

PS: I will be updating the files and the intro text on this page as I come across more information.

--------------------------------------------------------------------------------------

The csv file `somalia-aid-flow-2016-2018` has the following structure:

Field | Definition
-------| --------------
`project_title` | Name of the project as submitted by reporting agencies.
`project_objectives`| Summary details on the aims or rationale behind the intervention.
`start_date`| Project start date in `M/d/yy` format
`end_date` | Project end date in `M/d/yy` format
`ndp_pillar` | Project classification as defined by nine pillars of Somalia's National Development Plan.
`primary_sector` | A set of 25 aid and development sectors such health, education, PFM, WASH, Politics, etc.
`reporting_agency` | Refers to Somalia's Aid partners who voluntary share info on listed projects with ACU. Not all partners report their projects, major limitation of this dataset, see the full reports in the pdfs for more details.
`funders` | Project Donor. 
`implementers` | Primary institutions or organizations that carried out the project activities.
`implementer_category` |  General categories on the type of organizations implementing the activities i.e. NGO, UN, Military, Research, Government, etc.
`mtdf` | Which Multi Donor Trust Fund (mdtf) does the project make use of, if any.
`project_value` | Total value of the project in USD Dollars. ACU convered to dollars all projects whose value was reported in other currencies.
`project_url` | Project website where you can hopefully find more information.
`year` | The year when the funds were disbursed.
`amount_disbursed` | Amount disbursed per project per year.
`recipient` | The geographic entity or federal authority in whose territory the funds were spent in.
