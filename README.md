# One_Liners


### BASH

wget -r --user USERNAME --password PASSWORD LINK

LFTP:


Upload reads to ENA:
```bash
ftp webin.ebi.ac.uk
# username = Webin-49292

bin
prompt
mput *fastq.gz # or whatever file

```


### R
Save a csv or similar in R from a Windows environment without row names being saved to the file:

`write.csv(DATAFRAME, "FILENAME.csv", row.names = FALSE)`


