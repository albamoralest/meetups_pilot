# Queries and usage

Generate list of biographies and related files.
```
fx -q queries/list-sample.sparql -o data/biographies.csv -f CSV
```
Generate KG data
```
fx -q queries/meetups.sparql -i data/biographies.csv -p "data/meetups/?fileId.ttl" -f TTL
```
Statistics:
```
$ fx -q queries/statistics.sparql -l data/meetups/
-------------------------------
| key                 | value |
===============================
| "Meetups"           | 74445 |
| "Persons mentioned" | 51425 |
| "Subjects"          | 1002  |
| "Places mentions"   | 5595  |
| "Time expressions"  | 79838 |
-------------------------------
```
