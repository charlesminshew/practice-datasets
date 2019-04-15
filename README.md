# practice-datasets
Right now this includes two datasets that can be used for testing in R.

## Bridges
This is a slice of data from the 2018 National Bridge Inventory. Columns include:

| Column        | Short Name           | Description  |
| ------------- |:-------------| :-----|
| st_abbv      | State Abbreviation | Standard postal abbreviations |
| rectype      | Record Type      |   Example: 1 = Highway |
| rtnum | Route Number      |    The bridge's route number, if it has one. |
| strcture | Structure ID      |    The structure number as decided by state. |
| latmap | Latitude      |    The latitude of the bridge. |
| longmap | Longitude      |    The longitude of the bridge. |
| year | Year      |    The year the bridge was built. |
| bridgecond | Bridge Condition      |    Condition of the bridge. G = Good; F = Fair; P = Poor |

## Dams
This is a slice of data from the 2018 National Inventory of Dams. Columns include:

| Column        | Short Name           | Description  |
| ------------- |:-------------| :-----|
| city      | City | The closest city to the dam. |
| state      | State      |   The 2-letter postal code for the state. |
| dam_name | Dam Name      |    The name of the dam. |
| river | River      |    The river or other body of water the dam is located on. |
| year_completed | Year completed      |    The year the dam was completed. |
| hazard | Hazard      |    The hazard rating of the dam. Not the condition, but what's the likely outcome if a dam fails? L = Low; S = Significant; H = High; U = Undetermined. Low and signficant means there is a possibility of some level of economic disruption, but no loss of life. A high hazard rating means there is the chance of at least one death. |
| eap | Emergency Action Plan      |    Does the dam have an EAP? Y = Yes; N = No; NR = Not Required |
| latitude | Latitude     |   Latitude of the Bridge |
| longitude | Longitude      |    Longitude of the Bridge |
