***Colorado Board of Elections in Election Audit***

**Overview**

The goal of this exercise is to generate a vote counting report to certify the
US congressional race in Colorado. The scenario is that this election audit of
the tabulated results for U.S Congressional precinct was requested by Colorado
Board of Elections. The task is to report the total number of votes cast and
total number of votes and its percentage for each candidate, and the winner of
the election based on the popular votes. Another aim is to build a successful
code that can be used to audit future congressional district and possibly also
senatorial district and local elections. The data provided to be audited
contains votes from three primary voting methods, mail-in ballots, punch cards
and direct recording electronic (DRE counting machine).

In this analysis Python was utilized to extract and summarize voting data from
dataset of \~400,000 ballots. The data consists of a number for the ballot ID
and a name for the county and candidate. All this was analyzed and desired
results were reached (Figure 01)

**The Results of Election-Audi**

-   **The total votes** casted in the congressional election:  
    *369,711*

-   **Voting results by county** are follow:

-   Jefferson: 10.5% (38,855)

-   Denver: 82.8% (306,055)

-   Arapahoe: 6.7% (24,801)

Which makes *Denver* the county with the highest voter turnout.

-   **Voting results by candidate** are as follow:

-   Charles Casper Stockham: 23.0% (85,213)

-   Diana DeGette: 73.8% (272,892)

-   Raymon Anthony Doane: 3.1% (11,606)

The winner of the election was **Diana DeGette** with a total vote of
**272,892**, what makes **73.8%** of the total votes.

*![Text Description automatically
generated](resources/09c814fe16b82b54c3d50c0f0d7d2b7f.PNG)*

*Figure 01: Snipped after printing the python code to VS Code terminal.*

**Election-Audit Summary**

As mentioned, Python code was used to define the variables for the candidates
and counties depending on the available data. This code could be modified to
include other variables if given more categories of interest to work with such
as voting methods, voters ages, education, income, etc. It could be also be
modified to used for other similar campaign and data set in another state or
counties by redefining the variables.
