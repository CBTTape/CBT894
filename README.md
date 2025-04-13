# CBT894
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 894 is from Robert Zenuk by way of Sam Golob.  This       *   FILE 894
//*           collection of members was taken from several years'   *   FILE 894
//*           worth of posts to the MVS-OE listserv group, under    *   FILE 894
//*           Rob's name.  The code he posted, or the piece of      *   FILE 894
//*           thread which he wrote, which covered an issue, with   *   FILE 894
//*           a problem solved, is brought here as a single         *   FILE 894
//*           member, or several.                                   *   FILE 894
//*                                                                 *   FILE 894
//*           It is up to the user to see if he/she can benefit     *   FILE 894
//*           from this code and these posts.  They were brought    *   FILE 894
//*           here to help those who might need it.                 *   FILE 894
//*                                                                 *   FILE 894
//*           email:  Rob Zenuk <Robzenuk@AOL.COM>                  *   FILE 894
//*                                                                 *   FILE 894
//*           email:  Sam Golob <sbgolob@cbttape.org>               *   FILE 894
//*                                                                 *   FILE 894
//*                  Some of Rob Zenuk's stuff                      *   FILE 894
//*                  ---- -- --- ------- -----                      *   FILE 894
//*                                                                 *   FILE 894
//*    UNIXCMDB - TSO command to execute UNIX commands and to       *   FILE 894
//*               display the results.                              *   FILE 894
//*                                                                 *   FILE 894
//*               A version of an exec by John McKown.  Purpose     *   FILE 894
//*               is to execute UNIX commands from TSO, without     *   FILE 894
//*               using a UNIX shell.  I made this name longer      *   FILE 894
//*               because there were several variants posted on     *   FILE 894
//*               the MVS-OE list, but this one (or whichever       *   FILE 894
//*               variant you really use) should be renamed to      *   FILE 894
//*               be called UNIX.                                   *   FILE 894
//*                                                                 *   FILE 894
//*               model:  TSO UNIX unixcmd                          *   FILE 894
//*                                                                 *   FILE 894
//*    USSFILMT - TSO command to list UNIX files and how they       *   FILE 894
//*               are mounted.                                      *   FILE 894
//*                                                                 *   FILE 894
//*    USSGETMT - TSO command to display all file mounts            *   FILE 894
//*               under UNIX.                                       *   FILE 894
//*                                                                 *   FILE 894
//*               FULL LIST OF MEMBERS IN THIS PDS                  *   FILE 894
//*               ---- ---- -- ------- -- ---- ---                  *   FILE 894
//*                                                                 *   FILE 894
//*         $CONTENT  01.02  2013/08/11 17:29     24 SBGOLOB        *   FILE 894
//*         $LSTHZFL  01.00  2013/08/11 19:27     26 SBGOLOB        *   FILE 894
//*         @FILE894  01.03  2013/09/01 21:07      2 SBGOLOB        *   FILE 894
//*         BPXEXIST  01.01  2013/09/01 18:02     77 SBGOLOB        *   FILE 894
//*         BPXJCL    01.11  2013/08/14 23:40    245 SBGOLOB        *   FILE 894
//*         BPXJCL@   01.00  2013/08/14 23:56     27 SBGOLOB        *   FILE 894
//*         BPXJCL01  01.18  2013/08/14 23:42    218 SBGOLOB        *   FILE 894
//*         BPXJCL02  01.01  2013/08/15 14:54     23 SBGOLOB        *   FILE 894
//*         BPXSPOOL  01.01  2013/08/15 14:15    282 SBGOLOB        *   FILE 894
//*         BPXWGDG   01.00  2013/08/14 22:55     54 SBGOLOB        *   FILE 894
//*         BPXWUNIX  01.01  2013/08/13 14:11    297 SBGOLOB        *   FILE 894
//*         EZAZTSAB  01.00  2012/07/08 13:33     12 SHOW721        *   FILE 894
//*         EZAZTSEB  01.00  2012/07/08 13:33     44 SHOW721        *   FILE 894
//*         FINDSTR   01.00  2013/08/15 11:27     82 SBGOLOB        *   FILE 894
//*         GETSTAC@  01.00  2013/08/14 12:01     42 SBGOLOB        *   FILE 894
//*         GETSTACK  01.00  2013/08/14  0:30      8 SBGOLOB        *   FILE 894
//*         MNTCKDOC  01.00  2013/08/16 13:29     69 SBGOLOB        *   FILE 894
//*         MVSREXX   01.00  2013/08/15  0:07     92 SBGOLOB        *   FILE 894
//*         PDSSPLI@  01.02  2013/08/13 15:08   1203 RZENUK         *   FILE 894
//*         PDSSPLIJ  01.02  2013/08/13 15:18     24 JCL            *   FILE 894
//*         PDSSPLIT  01.01  2013/08/13 15:08   1098 EXEC           *   FILE 894
//*         QUICKXMI  01.00  2013/08/14 21:03     61 SBGOLOB        *   FILE 894
//*         RESTJOB   01.00  2013/08/16  9:39     60 SBGOLOB        *   FILE 894
//*         REXECX    01.00  2013/08/14 22:08    131 SBGOLOB        *   FILE 894
//*         SDSF2ZFS  01.00  2013/08/11 17:47    154 RZENUK         *   FILE 894
//*         SYMREP    01.02  2013/08/14 22:10    164 SBGOLOB        *   FILE 894
//*         UNIXCMD$  01.00  2013/08/11 15:29     32 SBGOLOB        *   FILE 894
//*         UNIXCMDB  01.01  2013/08/11 15:13     18 RZENUK         *   FILE 894
//*         USSFILM$  01.00  2013/08/11 19:18      9 SBGOLOB        *   FILE 894
//*         USSFILMT  01.00  2013/08/11 14:39      8 RZENUK         *   FILE 894
//*         USSGETMT  01.04  2013/08/11 14:27     89 RZENUK         *   FILE 894
//*                                                                 *   FILE 894
```
