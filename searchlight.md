## Searchlight

### Client

This section in Encore contains data about the client company for which a search is being conducted.

Field         | Type | Definition                                       | Format/Notes 
--------------|:----:|--------------------------------------------------|-------------
Company       | STR  | Name of company                                  | 
Description   | STR  | Title of search in Encore                        | 
Representative| STR  | Point person from company, looking to place exec |
Location      | STR  | Headquarters of client company                   |
Workgroup     | list | How Caldwell categorizes this / industry         |
Search type   | list | 
Code          | 
More Reps     |


### Instant Status

This section in Encore contains data on the status of each candidate being considered for a particular search.

Field             | Type     | Definition                                       | Format/Notes 
------------------|:--------:|--------------------------------------------------|-------------
Person            | STR      | Name of candidate                                | When you double-click, you can deep dive into the candidate's profile.
Current Company   | STR      | Name of company Person is currently employed by  | 
Date On           | DATETIME | Date search is first entered into Encore         |
Date Off          | DATETIME |                                                  |
Instant Status    | list     | <ul><li>01 To Be Contacted</li><li>02 Will Not Contact</li><li>03 Contact Initiated</li><li>04 Source</li><li>05 Not Interested</li><li>06 Prospect</li><li>07 Prospect - Not Qualified</li><li>08 TCP Interviewed</li><li>09 Candidate</li><li>10 Client Rejection</li><li>11 Candidate Rejection</li><li>12 Placement</li><li>13 Reference</li><li>14 By-Product</li><li>15 Client Rep</li><li>Ad Response</li><li>Ad Response NQ</li><li>Benchmark</li><li>Non-responsive</li><li>Wrong Contact</li><li>zCromwell</li></ul> |
User              | STR      | 
Summary           | STR      | Partner name                                     |  When you hover you get workgroup and city
For Client        | STR

ref: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables
