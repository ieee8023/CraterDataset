

This command was used to create this dataset:

```
cd RobbinsCraterDatabase_20121016.tab
cat RobbinsCraters_20121016.csv | awk {'print $3 "," $2 "," $6*1000 ",-16777216,ID:" $1 ","'} >> RobbinsCraters_20121016_JMars.csv
```