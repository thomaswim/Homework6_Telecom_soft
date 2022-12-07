# Homework6_Telecom_soft

### Request is the Homework tasks and Swimming Crawling is the example 5 with personnal project 

## Description of the algorithm of Swimming Crawling  :

This algorithm aims to browse all live swimming competitions on this website: https://www.liveffn.com/cgi-bin/liste_live.php

For each competition, the script retrieves the data from the page using requests. Then, it parse the data using beautiful soup. For each competition, we check the presence of a particular club: here it is the swimming club named "TOEC". If a swimmer of "TOEC" is present at this competition, it retrieves the data: The results and the commitments. Then, the script arranges all these data to create a JSON file readable and ordered. At the end of all the competitions, the script exports the Results and the Commitments in Json and Javascript files.
