# Methodology and Approach

Phase 1:  
 1 Obtain a list of zip codes along the San Andreas fault.
 2 Obtain property value information for zip codes, such as average home sale price.
	- Calculate price per sq foot (parcel size)
 3 Determine sq footage for each zip code
 4 Estimate zip code using average price per sq foot * number of sq ft in zip code
 5 Total all zip codes for estimated budgetary requirements 

Advantages: Market data readily available for quick and dirty budgetary estimate.
Disadvantages: Low accuracy.  

Output: Ranked ordred list by zip code


Phase 2:
 1 Determine Lat/Long for SAF (US Geological Survey)
 2 Query Google API for address and/or parcel number list
 3 Determine tax assessment for each address / parcel
 4 Total all assessments

Advantages: Higher accuracy.
Disadvantages: 

Output: Ranked ordered list by parcel or address

