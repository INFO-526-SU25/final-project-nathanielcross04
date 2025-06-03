# Data

-   **National Science Foundation Grant Terminations:** The NSF Grant Terminations dataset yields from [Grant Watch](https://grant-watch.us/nsf-data.html), an independent project whose goal is to track the termination of scientific research grants under the Trump Administration's second term (beginning in 2025). It is led by [Noam Ross](https://www.noamross.net/), a computational researcher and Executive Director of rOpenSci, and [Scott Delaney](https://hsph.harvard.edu/profile/scott-delaney/), a research scientist at Harvard University's Department of Environmental Health. Data is sourced largely by submissions from affected investigators and researchers at institutions across the United States, as well as from user-submitted lists of terminated grants, all of which are corroborated via the NSF's [Award Search](https://www.nsf.gov/awardsearch/) function and [USAspending.gov](https://www.usaspending.gov/). This dataset was found on [TidyTuesday](https://github.com/rfordatascience/tidytuesday/blob/main/data/2025/2025-05-06/readme.md#nsf_terminationscsv).

# Codebook for NSF Grant Terminations Dataset

## Variable Names and Descriptions:

-   **Grant Number:** the numeric ID of the grant.
-   **Project Title:** the title of the project the grant funds.
-   **Termination Letter Date:** the date a termination letter was received by the organization.
-   **Organization Name:** the name of the organization or institution funded to conduct the research.
-   **Organization City:** the name of the organization's city.
-   **Organization State:** the two-letter state abbreviation of the organization's state.
-   **Organization District:** the congressional district (state and number) where the organization is located.
-   **Obligated Spending:** the amount of spending, via USAspending.gov, that the NSF had committed to funding.
-   **Award Type:** the type of grant.
-   **Directorate Abbreviation:** the three-letter abbreviation of the NSF directorate name.
-   **Directorate:** the NSF directorate (the highest level of organization) which administered the grant.
-   **Division:** the NSF division (housed within directorates) which administered the grant.
-   **NSF Program Name:** the name of the funding program under which the grant was made.
-   **NSF URL:** the URL pointing to the award information in the public NSF award database.
-   **USA Spending URL:** the URL pointing to budget and spending information at the public USAspending.gov website.
-   **NSF Start Date:** the start date of the project.
-   **NSF Expected End Date:** the date the project was expected to end.
-   **Organization ZIP Code:** the five- or nine-digit ZIP code of the organization receiving the grant.
-   **Organization UEI:** The unique entity identifier (UEI) of the organization receiving the grant, used across U.S. government databases.
-   **Abstract:** the text of the project abstract describing the work to be done.
-   **Cruz List:** whether the project was in a list of NSF projects named by U.S. Senator Ted Cruz that he claimed "promoted Diversity, Equity, and Inclusion (DEI) or advanced neo-Marxist class warfare propaganda."

## Data Types:

-   **grant_number:** character
-   **project_title:** character
-   **termination_letter_date:** date
-   **org_name:** character
-   **org_city:** character
-   **org_state:** character
-   **org_district:** character
-   **usaspending_obligated:** double
-   **award_type:** character
-   **directorate_abbrev:** character
-   **directorate:** character
-   **division:** character
-   **nsf_program_name:** character
-   **nsf_url:** character
-   **usaspending_url:** character
-   **nsf_startdate:** date
-   **nsf_expected_end_date:** date
-   **org_zip:** character
-   **org_uei:** character
-   **abstract:** character
-   **in_cruz_list:** logical
