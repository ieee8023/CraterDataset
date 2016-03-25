

This command was used to create this dataset:

```
cd RobbinsCraterDatabase_20121016.tab
cat RobbinsCraters_20121016.csv | awk {'print $3 "," $2 "," $6*1000 ",-16777216,ID:" $1 ","'} >> RobbinsCraters_20121016_JMars.csv
```

In the awk script the varables line up to these columns in the dataset:

$1 = CRATER_ID

$2 = LATITUDE_CIRCLE_IMAGE

$3 = LONGITUDE_CIRCLE_IMAGE

$6 = DIAM_CIRCLE_IMAGE
