SQL injection strings - used by 28005, SQL Injection in URI

| SQL Injection Strings                                                |
|----------------------------------------------------------------------|
| SQL injection - insert,from,select,union,where - with or without %20 |
| %20SELECT *                                                          |
| %20select%20 *                                                       |
| %20union%20all%20select                                              |
| %20UNION%20SELECT                                                    |
| %20UNION%20select                                                    |
| %20UNION%20select AND %20from *                                      |
| %20union%20select%20                                                 |
| %20UNION%20SELECT%20 AND %20from%20 *                                |
| %20UNION%20select%20load_file('/etc/passwd')                         |
| %20WHERE AND %20SELECT%\\                                            |
| +union+select+                                                       |
| DECLARE%20                                                           |
| SELECT FROM                                                          |
| SET%20                                                               |
