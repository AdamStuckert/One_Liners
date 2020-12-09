# One_Liners


### BASH

wget -r --user USERNAME --password PASSWORD LINK

LFTP:

```bash
lftp adam.stuckert@unh.edu@ftp.box.com
# put will place files
# ls lists directory in remote
# !ls lists directory in local
# lcd changes directory in local
# cd changes directory in remote
```

FTP:
```bash
ftp
open $link
# to pull data:
get $FILE
to push data:
put $FILE
```

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


