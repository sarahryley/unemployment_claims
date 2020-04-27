# Introduction

The Fuller Project analyzed data from the U.S. Labor Department and various state agencies for the story [Coronavirus Shutdowns Make Women the Majority of Unemployment Seekers in States Across U.S.](https://fullerproject.org/story/coronavirus-shutdowns-make-women-the-majority-of-unemployment-seekers-in-states-across-u-s/), published April 22, 2020.

We requested weekly breakdowns of initial unemployment claims from every state, from March 1 through April 11, by gender, race, ethnicity, age, industry and occupation. Seventeen states provided some or all of the information requested, either via special request or by publishing it online. 

For a historic benchmark, we analyzed the U.S. Labor Department's ["Characteristics of the Insured Unemployed"](https://oui.doleta.gov/unemploy/chariu.asp) data, from 1995 through 2019. This data includes state-by-state demographic, industry, and occupation breakdowns of the total number of people receiving unemployment insurance during the week of the month that includes the 19th. (See note below, "insured" claims are not the same as "initial" claims)

# State data sources

The statistics from the state agencies generally include the same variables as their reports for the federal government. We manually standardized the statistics into a single spreadsheet to conform to the federal data. The following source notes were accurate as of publication. Agencies, including those not listed here, may have since changed the information they publish online.

| State | Source Note |
|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Alabama | Alabama Department of Labor emailed statistics, uploaded to [DocumentCloud](https://www.documentcloud.org/search/Project:%20%22Initial%20Unemployment%20Claims%22). |
| Alaska | Alaska Department of Labor emailed statistics, only a gender breakdown for one week, uploaded to [DocumentCloud](https://www.documentcloud.org/search/Project:%20%22Initial%20Unemployment%20Claims%22). |
| Idaho | Idaho Department of Labor statistics available [online](https://lmi.idaho.gov/ui-weekly-claims). |
| Minnesota | Minnesota Department of Employment and Economic Development statistics available [online](https://mn.gov/deed/data/data-tools/unemployment-insurance-statistics/). |
| Montana | Montana Department of Labor & Industry emailed Excel file, csv in folder. |
| Nebraska | Nebraska Department of Labor emailed Excel file, csv in folder. |
| New Jersey | New Jersey Department of Labor and Workforce Development emailed weekly breakdowns, uploaded to [DocumentCloud](https://www.documentcloud.org/search/Project:%20%22Initial%20Unemployment%20Claims%22). |
| New Mexico | New Mexico Department of Workforce Solutions emailed Excel file, csv in folder. |
| New York | New York State Department of Labor statistics available [online](https://labor.ny.gov/stats/weekly-ui-claims-report.shtm). |
| North Dakota | North Dakota Department of Labor Market Information statistics available [online](https://www.ndlmi.com/gsipub/index.asp?docid=687). |
| Ohio | Ohio Department of Job and Family Services monthly statistics available [online](https://ohiolmi.com/portals/206/UC/monthly/UC237cd_2003.pdf). |
| Oklahoma | Oklahoma Department of Commerce monthly statistics available [online](http://esrgc.org/dashboards/okdashboard/unemployment/index). |
| Oregon | Oregon Employment Department statistics available [online](https://www.oregon.gov/EMPLOY/Agency/Pages/UI-Reports.aspx) |
| Rhode Island | Rhode Island Department of Labor and Training provided Excel spreadsheet, csv in folder. |
| Utah | Utah Department of Workforce Services emailed statistics, uploaded to [DocumentCloud](https://www.documentcloud.org/search/Project:%20%22Initial%20Unemployment%20Claims%22). |
| Virginia | Virginia Employment Commission Economic Information & Analytics sent Excel file, csv in folder. |
| Wyoming | Wyoming Department of Workforce Services statistics available [online](https://public.tableau.com/views/WyomingUIClaimsCountbyWeek/UIClaimsCountbyDemographicsandWeek). |

Dates of school, restaurant, and workplace closures were pulled from the [National Governors Association](https://www.nga.org/coronavirus/), press releases, and articles.

Field definitions can be found [here](https://github.com/sarahryley/ui_analysis/blob/master/Notes/field_notes.csv).

# Other notes:

The analysis compares demographic and industry breakdowns of initial claims, provided by the states, with the U.S. Labor Department's demographic and industry breakdowns of continued claims. The U.S. Labor Department does not publish similar data on initial claims. These are not the same. From the department:

>An **initial claim** is a claim filed by an unemployed individual after a separation from an employer. The count of U.S. initial claims for unemployment insurance is a leading economic indicator because it is an indication of emerging labor market
conditions in the country. A person who has already filed an initial claim and who has experienced a week of unemployment then files a **continued claim** to claim benefits for that week of unemployment. Continued claims are also referred to as insured unemployment. Continued claims reflect the current number of insured unemployed workers filing for UI benefits in the nation.

State agencies did not provide consistent groupings for race and ethnicity. We standardized the groupings to conform to the federal data to the extent possible. In addition, tracking changes in the total and share of “white” applicants is problematic because the data only disaggregates totals by one characteristic at a time, separating race and ethnicity. Most Latinos choose “white” for race.

# Use Disclaimer

We are sharing our data, documentation, and code in order to support further research and reporting on unemployment claims. However, users of this data should independently verify the accuracy of their findings prior to making them public, as The Fuller Project makes no representations or warranties as to any third party use of these materials.

# Licensing

All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). All output data files are available under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) license.

# Questions?

For questions or feedback, please contact [Sarah Ryley](sarahryley@gmail.com).
