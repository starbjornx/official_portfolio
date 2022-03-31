API information for APEX LEGENDS addon to my Portfolio for fun

API KEY:
Key: VYvYJdCkzQAIgb9vzaaJ

https://apexlegendsapi.com/documentation.php

Request example:

GET https://api.mozambiquehe.re/bridge?version=5&platform=PC&player=HeyImLifeline&auth=YOURAPIKEY

You can also query multiple players at the same time, response will be as an array of players. The more players you add, the longer the query will take:

GET https://api.mozambiquehe.re/bridge?version=5&platform=PC&player=PlayerA,PlayerB,PlayerC&auth=YOURAPIKEY

UID query
You can query users by their UIDs, multiple UID queries will also work with the syntax above. Example query:

GET https://api.mozambiquehe.re/bridge?platform=PC&uid=1000575543540&auth=YOURAPIKEY
