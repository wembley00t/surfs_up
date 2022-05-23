# Surfs_Up

## Overview of Analysis

W. Avy, a potential investor, for the Surf n'Shake Shop wants more information about temperature trends before opening the surf shop in Hawaii. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. 

This analysis will include:

* Summary statistics for the month of June
* Summary statistics for the month of December
* Report for the analysis including two additional queries

## Results 

The analysis generated 2 tables.

The first table shows the level temperature statistics for the month of June.

![June Temps DB](https://user-images.githubusercontent.com/100876517/169726802-e4977deb-8529-4934-876c-71260f9fa20f.png)


The second table shows the level temperature statistics for the month of December.

![Dec Temps DB](https://user-images.githubusercontent.com/100876517/169726808-f140debc-81d2-4c69-b135-b1a909b8ee52.png)

* The average temperature for the month of June is 75 degrees compared to 71 degrees for December.
* The max temperature for the month of June is 85 degrees compared to 83 degrees for December.
* The minimum temperature for the month of June is 64 degrees compared to 56 degrees for December.  
  This statistic reflects the most difference between the two months.

## Summary

In summary, the data shows that December is slightly cooler than June which is to be expected given the time of year.  However,
the data also shows the temperature in the 25th percentile for June is 73 degrees compared to 69 for December.  While December
may have some cooler days, the overall trends do not vary significantly.  The business plan should reflect lower volume for
December based on temperature changes to be conservative.

Two additional queries to provide more insight into the weather for June and December show precipitation data for each month.

The queries are highlighted below.

![June Additional Query](https://user-images.githubusercontent.com/100876517/169728215-7df98802-4f13-4a2b-8698-71e272e6bd56.png)


![Dec Additional Query](https://user-images.githubusercontent.com/100876517/169728307-259e20a7-e265-4bc3-9271-5855159abf21.png)

The result of this query show there are 21,209 employees with the birth date in 1952 or the first year of the "silver 
tsunami" to help the organization prepare by year.

![June Precip DB](https://user-images.githubusercontent.com/100876517/169728237-c63ad956-63ec-488c-a68d-7c8d19a63176.png)![Dec Precip DB](https://user-images.githubusercontent.com/100876517/169728246-b353b834-fcb2-4f99-afc0-8ace6188b0b5.png)


The original mentorship eligibility was based on birthdates in 1965.  The organization may want to consider employees
eligible for mentorship with birthdates in 1964 as well to provide a larger employee population for mentorship.

The query below is the updated query to include 1964 and 1965 in the mentorship eligibility category.

![Expanded mentorship query](https://user-images.githubusercontent.com/100876517/167327651-a1321e0a-43df-4582-9cf5-232a890c8c01.png)

The results of this query are below.  

![Expand Mentorship](https://user-images.githubusercontent.com/100876517/167328236-14087157-d385-4358-b1aa-2480d24abad7.png)

By expanding the mentorship eligibility to birthdates of 1964 and 1965, the total number of employees eligible has increased by
18,356 and in the much needed categories of Senior Engineer and Senior Staff.

