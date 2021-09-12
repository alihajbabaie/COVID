# COVID
This Branch includes COVID-19 vaccine allocation, shipment, and wastage data. The initial data covers a span of late december 2020 to the end of March 2021 and is being updated as more data become available. 

Vaccine shipment files have the following Data Fileds. The description of each field is given below:
PROVIDER_NAME:	The name of provider who administers vaccines
STREET_SHP:	the street address of the provider
STREET2_SHP:	The apartment, suite, unit, etc. of the provider; This field may be blank if the information is not reported or the provide does not have suite number. 
CITY_SHP:	the city of the provider
STATE_SHP:	the state of the provider
ZIPCODE_SHP: the zip code of the provider
PROVIDER_STATUS: Provider status: active, inactive, pending, or suspended
AWARDEE: The name of vaccine awardee: states/territories (e.g., Illinois, new york city, the Marshall Islands) and non-state/territories (e.g., CVS)
NDC: The	national drug code; it is a unique code used to identify and report drugs
NDC_DESCRIPTION: the description of NDC showing vaccine type, packaging, etc.
VAX_MANUFACTURER:	Vaccine manufacturer (e.g., Pfizer)
LOT_NUMBER:	the Lot number that can be used to determine the expiration date
LOT_EXPIRATION_DATE: the expiration date of the shipped lot; If shows 2069, the expiration date is not reported; Lot number should be entered in resources (32,33) to determine expiration date. 
ORDER_SHIPPED_DATE: the shipment date of the lot
DOSES_SHIPPED: the number of doses included in the shipment
LAST_REFRESH_DATE: The date the data was last updated
ORDER_NUMBER:	Order number
ORDER_LINE_NUMBER:	Order line number

Vaccine Wastage	data have the following data fields. The description of each field is given below: 
AWARDEE: the name of vaccine awardee: states/territories and non-state/territories
NDC_DESCRIPTION:	Description of NDC showing vaccine type, packaging, etc.
WASTAGE_SUBMITTED_DATE: the date that the vaccine wastage was reported
TotalDoses: the total number of doses wasted during the reporting period
