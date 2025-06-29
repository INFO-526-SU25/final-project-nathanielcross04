## Data overview

**1. National Science Foundation Grant Terminations:** The NSF Grant Terminations dataset yields from [Grant Watch](#0), an independent project whose goal is to track the termination of scientific research grants under the Trump Administration's second term (beginning in 2025). It is led by [Noam Ross](#0), a computational researcher and Executive Director of rOpenSci, and [Scott Delaney](#0), a research scientist at Harvard University's Department of Environmental Health. Data is sourced largely by submissions from affected investigators and researchers at institutions across the United States, as well as from user-submitted lists of terminated grants, all of which are corroborated via the NSF's [Award Search](#0) function and [USAspending.gov](#0). This dataset was found on [TidyTuesday](#0).

**2. National Science Foundation Grants**: The NSF Grants dataset is derived from [NSF by the Numbers](#0), the National Science Foundation's statistics and database portal, including information on funding information for grant awards, funded institutions and organizations, proposals for funding, and obligated spending per year since fiscal year 2011.

**3. State Partisanship:** The State Partisanship dataset is adopted from the [CNN Politics](https://www.cnn.com/election/2024/results/president?election-data-id=2024-PG&election-painting-mode=projection-with-lead&filter-key-races=false&filter-flipped=false&filter-remaining=false)' reporting on the 2024 presidential election, and details the candidate who won the electoral votes of each state.

## 1. Codebook for NSF Grant Terminations Dataset

### Variable names and descriptions:

-   **Termination Letter Date:** the date a termination letter was received by the organization.
-   **Organization State:** the two-letter state abbreviation of the organization's state.
-   **Obligated Spending:** the amount of spending, via USAspending.gov, that the NSF had committed to funding.
-   **Directorate:** the NSF directorate (the highest level of organization) which administered the grant.
-   **NSF Start Date:** the start date of the project.

### Data types:

-   **termination_letter_date:** date
-   **org_state:** character
-   **usaspending_obligated:** double
-   **directorate:** character
-   **nsf_startdate:** date

## 2. Codebook for NSF Grants Dataset

::: callout-note
This is a supplemental dataset, and can be found as `all_awards.csv` in the project repository.
:::

### Variable names and descriptions:

-   **Organization State:** the two-letter state abbreviation of the organization's state.

-   **Award Obligation to Date:** the amount of spending that the NSF had committed to funding.

### Data types:

-   **org_state:** character
-   **award_obligation_to_date:** double

## 3. Codebook for State Partisanship Dataset

::: callout-note
This is a supplemental dataset, and can be found as `all_awards.csv` in the project repository.
:::

### Variable names and descriptions:

-   **State:** the two-letter state abbreviation of the state.

-   **Vote for Trump:** a logical variable set to TRUE if the state's electoral votes were allocated to Trump.

### Data types:

-   **org_state:** character
-   **vote_trump:** logical
