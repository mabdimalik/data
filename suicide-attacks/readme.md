# Suicide Attacks in Mogadishu

This repo contains data extracted from the Armed Conflict Location and Event Data [ACLED](acleddata.com/data). This processed version includes only  a few relevant fields, verified incidents and new fields or corrections to existing ones including suicide `target`, number of suicide attacks `counts`, estimated number of `injuries` per attack. 

The data resulted in a visualization for this article [Nearly 4000 Killed, Wounded By Suicide Attacks in Mogadishu since 2012](https://abdimalik.com/nearly-4000-killed-wounded-by-suicide-attacks-in-mogadishu-since-2012/)

The csv file `suicide-attacks-mogadishu` has the following structure:

Column Name | Definition
----| ----------
`date` | Date of incident
`year`| Year when the incident happened
`target`| Per news sources, who was believed to have been the target of the attack
`fatalities` | Number of people killed, figures mostly from ACLED but in some instances include my corrections.
`count` | Number of suicide attackers if person borne or cars if it is a VBIED. 
`injuries` | Number of persons injured, from news sources, includes estimates esp. the 10s
`district` | District where the attack took place
`location` | Location of the attack, might not be exact. 
`latitude` | ACLEDs estimate of the location’s latitude.
`longitude` |  ACLEDs estimate of the location’s longitude.
`notes` | ACLEDs incident report.

