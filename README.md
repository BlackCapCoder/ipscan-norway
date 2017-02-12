## no.csv
A list of norwegian ip blocks that I got from nirsoft

## field
A directory with binary files, one for each ip block in no.csv, where every bit corresponds to one ip address in that block. 0 means that the ip address did not reply to a ping at Feb 10/2017.

## portscans
Lists of ip addresses that:
* Replied to my initial ping
* Had port x open

## indexof-sites
A list of all of the sites that are indexof sites

## indexof-sites-struct
The complete folder structure of all the indexof sites. Does not list files

## ssh-connect
List of ip addresses that:
* Replied to my initial ping
* Had port 22 open
* I was able to connect to over ssh within 15 seconds

Each entry also has a status, OK being things you can connect to
