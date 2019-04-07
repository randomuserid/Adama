Data layer searches for database threat activity

| Category                | Description                                                                            |
|-------------------------|----------------------------------------------------------------------------------------|
| Behavioral              | anomalous database client activity                                                     |
| Behavioral              | Anomalous database client activity                                                     |
| Behavioral              | Anomalous process on database server                                                   |
| Behavioral              | Anomalous SQL command activity                                                         |
| Behavioral              | anomalous SQL sessions                                                                 |
| Behavioral              | authorization failures                                                                 |
| Behavioral              | Shell commands by database server process                                              |
| Behavioral              | Shell commands by database server user context                                         |
| Collection              | database dump                                                                          |
| Collection              | database query written to a text file                                                  |
| Behavioral Detection    | selects of honeytokens - false records with high value created to attract data thieves |
| Initial Access          | Anomalous database logins                                                              |
| mySQL Linux execution   | CREATE FUNCTION * "*.so"*                                                              |
| mySQL Linux execution   | mySQL downloads                                                                        |
| mySQL Linux execution   | SELECT * *.so                                                                          |
| mySQL Linux execution   | SELECT * ./* *                                                                         |
| mySQL Linux execution   | SELECT * curl*                                                                         |
| mySQL Linux execution   | SELECT * http*                                                                         |
| mySQL Linux execution   | SELECT * wget*                                                                         |
| mySQL Windows execution | CREATE * '*.dll'                                                                       |
| mySQL Windows execution | SELECT *'*.exe'                                                                        |
| mySQL Windows execution | SET * *.dll                                                                            |
| Network                 | database connection from the Internet                                                  |
| Network                 | elasticsearch connection from the internet                                             |
| Persistence             | schema and configuration changes from remote hosts                                     |
| Behavioral Detection    | Suspicious query rates                                                                 |
| Behavioral Detection    | Honeytoken access                                                                      |
