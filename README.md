# Data Source
https://tianchi.aliyun.com/dataset/151847

The entire dataset disclosure application is in progress and will be released later.


# Data Format

## user_behavior_item_sample.csv
The data set covers all behaviors (including clicks, favorites, adding, and purchases) of approximately 62M million random users from September 3, 2022 to December 3, 2022. The organization of the data set as fllows, namely Each row of the collection represents a user data behavior, which is composed of user ID, Item ID, behavior type, and Timestamp log. Each column summarizes the detailed information of the product under investigation.
| Field | Explanation |
| --- | --- |
| User ID | An integer, the serialized ID that represents a user |
| Item ID | An integer, the serialized ID that represents an item |
| Behavior type | A string, enum-type from ('browsing', 'click', 'pay') |
| Timestamp | An integer, the timestamp of the behavior |


## user_profile.csv
This data set mainly contains the basic attributes of about five million random users, such as age, gender, occupation, resident city ID, crowd tag, etc. Each row of the data set represents a piece of user information, separated by commas. The detailed description of each column in the data set is as follows:
| Field | Explanation |
| --- | --- |
| User ID | An integer, the serialized ID that represents a user |
| Age | An integer, the serialized ID that represents an user age |
| Gender | An integer, the serialized ID that represents the user gender |
| Occupation | An integer, the serialized ID that represents the user occupation |
| Habitual City | An integer, the serialized ID that represents the user habitual city，single value |

## item_profile.csv

This data file mainly contains the basic attribute characteristics of about 34M products, such as product picture infomations and text infomations. Each row of the data set represents the information of a item, separated by commas. The detailed description of each column in the data set is as follows:
| Field | Explanation |
| --- | --- |
| Item ID | An integer, the serialized ID that represents an item |
| Category ID | An integer, the serialized ID of the first leg of the train number |
| Creative Picture Tag IDs | A String, the ID of each tag is separated by English semicolon after serialization |
| Creative Text Tag IDs | A String, the ID of each tag is separated by English semicolon after serialization |
|
