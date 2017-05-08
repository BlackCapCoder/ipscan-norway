# ipscan-norway
This is a complete scan of all Norwegian owned ip blocks. They are mostly home networks or state owned.
I only scanned certain ports, and only if the addresses replied to a ping first.
This project aims to help the respective owners close their ports. If you are on either of these lists and don't want to be, do let me know.

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

## ftp-connect
List of ip addresses that:
* Replied to my initial ping
* Had port 21 open
* I was able to connect to over ftp within 1 second

Each entry also has a status, OK being things you can log in to as anonymous

## ftp-connect-ok
Only the OK's from ftp-connect

## ftp-struct
List of all files and directories in the root folder of all open ftp servers on the list

## smb-open
List of open smb servers

## Footnotes
* All of the 146.2.* addresses in portscan502 are used by the Norwegian traffic system. You may or may not be able to control the traffic lights
