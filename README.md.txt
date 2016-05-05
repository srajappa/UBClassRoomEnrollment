## Synopsis
Here a MapReduce application which runs on Hadoop Framework counts the number of students using a Hall at University at Buffalo for every semester since the year 1931. 
The input data (a .csv file) consists of information viz. Serial #, Room #, Semester, Capacity of a room, timings of the class etc. Moreover, the input data like any data source has incorrect data so this 
application also discards such entries.   

## Output Example
The output on running this application generates file(s) that contain Hall name with semester information and total number of enrollments.
The images below show sample input details and sample output.
![alt tag](https://lh3.googleusercontent.com/C-lR4qkSIlDicJLOnsjMMMcBDaDSeoSGKlzl-bjPq2_8Gjr8yTa2jYGU3txcAEadRgbnK_lS0Q_w_OeAeerZ_XI1HxEDIQ-ljO0rzkpQj8D9aZQqd5ovGSnjt4Ynu9B7GfdrK9QkwPkggdU4tB4tYAtT1LIdLt4Ugn5ZRKfp_ExUeLHG0G1tyxeC0-CidECMfbxT9D6_S0qTHCITKm1LRC4Wdiw3joXUk9ZhCtuzIYzXgLIEX1RmynW6zZfp5AFmafSE90ay2J62Wgg6pLBDQayOqGF0IbxiP7kNYJ2Aq7ib39xwJSsX2C5utuOPkjEhEh6ZFbjQBnXSZChgIgtVfoxLA2VXfp2RzlNYcqeGoRFog1tgY85H8iMLkY_YrqQoRcncz0MtYB9_SW2DIGNXFTXCNlTRg7vjTeWubfF1j-lCX-2Ustns6_sjaGuX3SmtiCVDUia83ZS6oFJDeKJT_dYNN01T3LCDEsvmMW4cvCLE1mBJsJsBD27Bco6eEZRDRujizce7jOGf5Q3mvdrqvqxHQVZsVh-3vJbRpu_jD5QUyLaqQZH4to6tNBbGSaaR2vMZ7A=w1107-h408-no)

![alt tag](https://lh3.googleusercontent.com/TFbbvNb9DWzUK_Wcy5LzqeR_XkNtm-7UdaLqMCWq4Ij_xJcXBFTo7o7bCcyA3Nm9SRBBEqndcSDadu0I14YJgoXzt9-ssO20oeN8YS4MWPV_HPgY4UgKD5E5_oanDPJUY6GPAJEcFhHMKRceJTwqpPrZqx92LcSw8DN6syaQaTDbRDAp9xJXcnDHq3R1JjZJH4nk_rN-f5i0j7aQJhnGJL8jYlfd65Pi-GchObGm77G661wPWGp2j2CPbrdo7OnTZ_h88np-beqUR2lCw4EScgcr5-2SncAv7cDmbx0x08ic2nodPPby7gozCKBe3gfgGmV3X6enbuT6-nv4yDBmnigAPAe8VXUsCNBjOzPDr8Cj_WH8tFb7anRzqEUuqD_1-cQEN5kbFc_afkvEcZwDvkj59_8TAwCqrkGvQRQuh4Zbxh8P3P51fUHfKizAHgnso-55BDtP-vTP6ZSih5NQ1y_RdrGXgIXUPw37I17DsqaqX7P2zN9Gg3VMf3nai5mIjFC97FWqM7ImGzM1vaEBkLqYTOA3fNzNUKaMo8SrxnBMRuoj9z_GlEa65SGQTp_7BiqpKw=w524-h231-no)

## Running Application
The output of this application was run on Amazon Webservices System (AWS). A cluster was created in Elastic Map Reduce(EMR), and it produced the output. 

## Motivation
The application was a created as a part of Academic Project which was menteroed by Dr. Bina Ramamurthy.

## Sources
1. Apache Hadoop Online documentation : https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html
  