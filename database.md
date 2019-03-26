Data layer searches for database threat activity

| Category                | Description                                                                                                           |
|-------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Behavioral              | anomalous database client activity                                                                                    |
| Behavioral              | Anomalous database client activity                                                                                    |
| Behavioral              | Anomalous process on database server                                                                                  |
| Behavioral              | Anomalous SQL command activity                                                                                        |
| Behavioral              | anomalous SQL sessions                                                                                                |
| Behavioral              | authorization failures                                                                                                |
| Behavioral              | Shell commands by database server process                                                                             |
| Behavioral              | Shell commands by database server user context                                                                        |
| Collection              | database dump                                                                                                         |
| Collection              | database query written to a text file                                                                                 |
| Correlation             | authorization failures followed by success                                                                            |
| Correlation             | database errors followed by exfil                                                                                     |
| Correlation             | database failures followed by success                                                                                 |
| Correlation             | excessive schema or configuration change failures followed by success                                                 |
| Correlation             | successful user changes preceded by schema or configuration change failures                                           |
| Fraud                   | detecting anomalous access e.g. users accessing tables or rows they rarely or never normally do                       |
| Fraud                   | detecting identifiable specific patterns of misuse like 'select * from account where accountbalance > 1000'           |
| Fraud                   | detecting inappropriate selects e.g. customer service rep selecting financial data or non-rep selecting customer data |
| Fraud                   | detecting large number of selects                                                                                     |
| Fraud                   | many database queries during one call                                                                                 |
| Fraud                   | selects of honeytokens - false records with high value created to attract data thieves                                |
| Fraud                   | watching for selects of customer records outside the user's assigned territory                                        |
| Logs                    | Anomalous database logins                                                                                             |
| mySQL Linux execution   | CREATE FUNCTION * "*.so"*                                                                                             |
| mySQL Linux execution   | mySQL downloads                                                                                                       |
| mySQL Linux execution   | SELECT * *.so                                                                                                         |
| mySQL Linux execution   | SELECT * ./* *                                                                                                        |
| mySQL Linux execution   | SELECT * curl*                                                                                                        |
| mySQL Linux execution   | SELECT * http*                                                                                                        |
| mySQL Linux execution   | SELECT * wget*                                                                                                        |
| mySQL Windows execution | CREATE * '*.dll'                                                                                                      |
| mySQL Windows execution | SELECT *'*.exe'                                                                                                       |
| mySQL Windows execution | SET * *.dll                                                                                                           |
| Network                 | database connection from the Internet                                                                                 |
| Network                 | elasticsearch connection from the internet                                                                            |
| Persistence             | schema and configuration changes from remote hosts                                                                    |
