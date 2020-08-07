google-political-ads-creative-stats.csv

This file contains the information for political ads that have appeared on
Google Ads Services. Ad-level targeting data was added to this file in April
2020.

Fields:
Ad_ID - Unique id for a specific political ad.
Ad_URL - URL to view the political ad in the Political Advertising on Google
report.
Ad_Type - The type of the ad. Can be TEXT, VIDEO or IMAGE.
Regions - The regions that this ad is certified for or were served in.
Advertiser_ID - ID of the advertiser who purchased the ad.
Advertiser_Name - Name of advertiser.
Date_Range_Start - First day a political ad ran and had an impression.
Date_Range_End - Most recent day a political ad ran and had an impression.
Num_of_Days - Total number of days a political ad ran and had an impression.
Ad_Campaigns_List - IDs of all political ad campaigns that included the ad.
Impressions - Number of impressions for the political ad. Impressions are
grouped into several buckets: ≤ 10k, 10k–100k, 100k–1M, 1M–10M, > 10M.
Spend_USD - [DEPRECATED] This field is deprecated in favor of specifying the
lower and higher spend bucket bounds in separate Spend_Range_Min and
Spend_Range_Max columns.
Spend_Range_Min_USD - Lower bound of the amount in USD spent by the advertiser
on the political ad.
Spend_Range_Max_USD - Upper bound of the amount in USD spent by the advertiser
on the political ad.
Spend_Range_Min_EUR - Lower bound of the amount in EUR spent by the advertiser
on the political ad.
Spend_Range_Max_EUR - Upper bound of the amount in EUR spent by the advertiser
on the political ad.
Spend_Range_Min_INR - Lower bound of the amount in INR spent by the advertiser
on the political ad.
Spend_Range_Max_INR - Upper bound of the amount in INR spent by the advertiser
on the political ad.
Spend_Range_Min_BGN - Lower bound of the amount in BGN spent by the advertiser
on the political ad.
Spend_Range_Max_BGN - Upper bound of the amount in BGN spent by the advertiser
on the political ad.
Spend_Range_Min_HRK - Lower bound of the amount in HRK spent by the advertiser
on the political ad.
Spend_Range_Max_HRK - Upper bound of the amount in HRK spent by the advertiser
on the political ad.
Spend_Range_Min_CZK - Lower bound of the amount in CZK spent by the advertiser
on the political ad.
Spend_Range_Max_CZK - Upper bound of the amount in CZK spent by the advertiser
on the political ad.
Spend_Range_Min_DKK - Lower bound of the amount in DKK spent by the advertiser
on the political ad.
Spend_Range_Max_DKK - Upper bound of the amount in DKK spent by the advertiser
on the political ad.
Spend_Range_Min_HUF - Lower bound of the amount in HUF spent by the advertiser
on the political ad.
Spend_Range_Max_HUF - Upper bound of the amount in HUF spent by the advertiser
on the political ad.
Spend_Range_Min_PLN - Lower bound of the amount in PLN spent by the advertiser
on the political ad.
Spend_Range_Max_PLN - Upper bound of the amount in PLN spent by the advertiser
on the political ad.
Spend_Range_Min_RON - Lower bound of the amount in RON spent by the advertiser
on the political ad.
Spend_Range_Max_RON - Upper bound of the amount in RON spent by the advertiser
on the political ad.
Spend_Range_Min_SEK - Lower bound of the amount in SEK spent by the advertiser
on the political ad.
Spend_Range_Max_SEK - Upper bound of the amount in SEK spent by the advertiser
on the political ad.
Spend_Range_Min_GBP - Lower bound of the amount in GBP spent by the advertiser
on the political ad.
Spend_Range_Max_GBP - Upper bound of the amount in GBP spent by the advertiser
on the political ad.
First_Served_Timestamp - The timestamp of the earliest impression for this ad.
Last_Served_Timestamp - The timestamp of the most recent impression for this ad.
Age_Targeting - Age ranges included in the ad's targeting.
Gender_Targeting - Genders included in the ad's targeting.
Geo_Targeting_Included - Geographic locations included in the ad's targeting.
Geo_Targeting_Excluded - Geographic locations excluded from the ad's targeting.

google-political-ads-advertiser-stats.csv

This file contains the information about advertisers who have run a political ad
on Google Ads Services with at least one impression.

Fields:
Advertiser_ID - Unique ID for an advertiser certified to run political ads on
Google Ads Services.
Advertiser_Name - Name of advertiser.
Public_IDs_List - List of public IDs used to identify the advertiser, if
available.
Regions - the list of regions where the ads of this advertiser were served
Elections - the list of elections that this advertiser participated in based on
the regions.
Total_Creatives - Total number of political ads the advertiser ran with at least
one impression.
Spend_USD - Total amount in USD spent on political ads by the advertiser.
Spend_EUR - Total amount in EUR spent on political ads by the advertiser.
Spend_INR - Total amount in INR spent on political ads by the advertiser.
Spend_BGN - Total amount in BGN spent on political ads by the advertiser.
Spend_HRK - Total amount in HRK spent on political ads by the advertiser.
Spend_CZK - Total amount in CZK spent on political ads by the advertiser.
Spend_DKK - Total amount in DKK spent on political ads by the advertiser.
Spend_HUF - Total amount in HUF spent on political ads by the advertiser.
Spend_PLN - Total amount in PLN spent on political ads by the advertiser.
Spend_RON - Total amount in RON spent on political ads by the advertiser.
Spend_SEK - Total amount in SEK spent on political ads by the advertiser.
Spend_GBP - Total amount in GBP spent on political ads by the advertiser.


google-political-ads-advertiser-weekly-spend.csv

This file contains the information for how much an advertiser spent on political
ads during a given week.

Fields:
Advertiser_ID - Unique ID for an advertiser certified to run political ads on
Google Ads Services.
Advertiser_Name - Name of advertiser.
Election_Cycle - [DEPRECATED] This field is deprecated in favor of the Elections
column in google-political-ads-advertiser-stats.csv. It will be deleted some
time after July 2019.
Week_Start_Date - The start date for the week where spending occurred.
Spend_USD - The amount in USD spent on political ads during the given week by
the advertiser.
Spend_EUR - The amount in EUR spent on political ads during the given week by
the advertiser.
Spend_INR - The amount in INR spent on political ads during the given week by
the advertiser.
Spend_BGN - The amount in BGN spent on political ads during the given week by
the advertiser.
Spend_HRK - The amount in HRK spent on political ads during the given week by
the advertiser.
Spend_CZK - The amount in CZK spent on political ads during the given week by
the advertiser.
Spend_DKK - The amount in DKK spent on political ads during the given week by
the advertiser.
Spend_HUF - The amount in HUF spent on political ads during the given week by
the advertiser.
Spend_PLN - The amount in PLN spent on political ads during the given week by
the advertiser.
Spend_RON - The amount in RON spent on political ads during the given week by
the advertiser.
Spend_SEK - The amount in SEK spent on political ads during the given week by
the advertiser.
Spend_GBP - The amount in GBP spent on political ads during the given week by
the advertiser.


[DEPRECATED] google-political-ads-campaign-targeting.csv

This file was deprecated and ad-level targeting information was made available
in the google-political-ads-creative-stats.csv file effective April 2020.

This file contains the information related to ad campaigns run by advertisers.

Fields:
Campaign_ID - [DEPRECATED] Unique ID for a political ad campaign.
Age_Targeting - [DEPRECATED] Age ranges included in the campaign's targeting.
Gender_Targeting - [DEPRECATED] Genders included in the campaign's targeting.
Geo_Targeting_Included - [DEPRECATED] Geographic locations included in the
campaign's targeting.
Geo_Targeting_Excluded - [DEPRECATED] Geographic locations excluded from the
campaign's targeting.
Start_Date - [DEPRECATED] Start date for the campaign.
End_Date - [DEPRECATED] End date for the campaign.
Ads_List - [DEPRECATED] List of Ad_IDs for the campaign.
Advertiser_ID - [DEPRECATED] ID of the advertiser who purchased the ad.
Advertiser_Name - [DEPRECATED] Name of advertiser.


google-political-ads-geo-spend.csv

This file contains the information for how much is spent buying political ads
on Google Ads Services. The data is aggregated by geography.

Fields:
Country - The country where political ads were served, specified in the
ISO 3166-1 alpha-2 standard code.
For example: "US" for United States.
Country_Subdivision_Primary - The primary subdivision of the country where
political ads were served, specified by the ISO 3166-2 standard code.
For example: "US-CA" for California state in United States.
Country_Subdivision_Secondary - The name of the secondary subdivision.
For example: The name of a US congressional district.
Spend_USD - Total amount in USD spent on political ads in this region.
Spend_EUR - Total amount in EUR spent on political ads in this region.
Spend_INR - Total amount in INR spent on political ads in this region.
Spend_BGN - Total amount in BGN spent on political ads in this region.
Spend_HRK - Total amount in HRK spent on political ads in this region.
Spend_CZK - Total amount in CZK spent on political ads in this region.
Spend_DKK - Total amount in DKK spent on political ads in this region.
Spend_HUF - Total amount in HUF spent on political ads in this region.
Spend_PLN - Total amount in PLN spent on political ads in this region.
Spend_RON - Total amount in RON spent on political ads in this region.
Spend_SEK - Total amount in SEK spent on political ads in this region.
Spend_GBP - Total amount in GBP spent on political ads in this region.


[DEPRECATED] google-political-ads-top-keywords-history.csv

The “Top Keywords” section of the US report was removed and updates to this file
were terminated in December 2019. The file reflects historical data.

This file contains the information for the top six keywords on which political
advertisers have spent money during an election cycle. This data is only
provided for US elections.

Fields:
Election_Cycle - [DEPRECATED] This field is deprecated in favor of the Region
and Elections field. It will be deleted some time after July 2019.
Region - [DEPRECATED] The region where advertisers used these keywords.
Elections - [DEPRECATED] The elections during which these keywords were used.
Report_Date - [DEPRECATED] The start date for the week where the spending was
reported.
Keyword_1 - [DEPRECATED] Keyword with the most spend by advertisers for
political ads
Spend_USD_1 - [DEPRECATED] Total spend in USD for Keyword_1.
Keyword_2 - [DEPRECATED] Keyword with the next most spend by advertisers for
political ads
Spend_USD_2 - [DEPRECATED] Total spend in USD for Keyword_2.
Keyword_3 - [DEPRECATED] Keyword with the next most spend by advertisers for
political ads
Spend_USD_3 - [DEPRECATED] Total spend in USD for Keyword_3.
Keyword_4 - [DEPRECATED] Keyword with the next most spend by advertisers for
political ads
Spend_USD_4 - [DEPRECATED] Total spend in USD for Keyword_4.
Keyword_5 - [DEPRECATED] Keyword with the next most spend by advertisers for
political ads
Spend_USD_5 - [DEPRECATED] Total spend in USD for Keyword_5.
Keyword_6 - [DEPRECATED] Keyword with the next most spend by advertisers for
political ads
Spend_USD_6 - [DEPRECATED] Total spend in USD for Keyword_6.


google-political-ads-updated.csv

This file contains the information of the latest updated date for the Political
Ads report. All dates provided are per UTC time zone.

Fields:
Report_Data_Updated_Date - The updated date is the date the report's data was
last refreshed.


google-political-ads-advertiser-declared-stats.csv

California requires some advertisers to submit additional data about themselves.
The advertiser is responsible for the accuracy of this information, which Google
has not confirmed. This information is provided from our express notification
process required for certain California advertisers, which is separate from our
verification process.

Fields:
Advertiser_ID - ID of the advertiser who purchased the ad.
Committee_Declared_Name - The advertiser’s committee declared name.
Committee_Declared_Identification_ID - Committee declared identification number.
Committee_Declared_Scope  - Committee-provided information about the candidate
and office or ballot proposition and jurisdiction to which the advertisement
refers, which is separate from our verification process.



For more information see:
The Political Advertising on Google Transparency Report at
https://transparencyreport.google.com/political-ads/home

The supporting Frequently Asked Questions at
https://support.google.com/transparencyreport/answer/9575640?hl=en&ref_topic=7295796

The  Political Advertising on google BigQuery public dataset at
https://console.cloud.google.com/marketplace/details/transparency-report/google-political-ads

