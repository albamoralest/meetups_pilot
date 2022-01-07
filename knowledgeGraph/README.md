# Queries and usage

Generate list of biographies and related files.
```
fx -q queries/list-sample.sparql -o data/biographies.csv -f CSV
```
Generate KG data
```
fx -q queries/meetups.sparql -i data/biographies.csv -p "data/meetups/?fileId.ttl" -f TTL
```