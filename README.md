# Iran Advertisement Numbers
A database of phone numbers used for SMS advertisement in Iran.

## Advertisement Type
| Type                    | Explanation |
| ----------------------- | ----------- |
| Ad                      | Basic Not Personalized Advertisement |
| Promotion               | Advertisement that is used to push short-term sales |
| Personalized Promotion  | A promotion that uses target user data to personalize it for the user. Sometimes contains special offers and user-specific discount codes |

## Black List
The file `ad-numbers-black-list.csv` contains a list of advertising phone numbers that do not have a recognizable pattern. The `Number` column is the phone number itself and the `Type` column is the type of advertisement applied by that phone number. 

## Pattern List
The file `pattern-numbers.csv` contains patterns of groups of advertising phone numbers with a recognizable pattern. The `Number` column is the pattern in which the character `*` is used for placeholders. The `Type` column is the type of advertisement applied by that phone number. 
