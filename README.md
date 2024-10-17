LNCPMV
======

LNCPMV - {ln,cp,mv}{date,note,time}

Use a single uility to link, copy or move a file with an extension based on the date, a note or the time.

If called as LNCPMV, creates the files listed in LIST below as hardlinks.

# Usage

```
  Usage: {LNCPMV,"{cp,mv}{date,note,time} {args}"}
  
  LNCPV   -- This utility, when run, will create hardlinks to itself.
  
  cp*     -- Copy a file
  cpbak   -- The new copied file will end in .bak
  cpdate  -- The new copied file will end with the `date`
  cpnote  -- The new copied file will end with a custom note
  cptime  -- The new copied file will end with the time
  
  mv*     -- Move a file
  mvbak   -- The moved file will end in .bak
  mvdate  -- The moved file will end with the `date`
  mvnote  -- The moved file will end with a custom note
  mvtime  -- The moved file will end with the time
```

# Original Credits

This is an ancient script from the Public Domain. It was passed around from
floppy disk to floppy disk, from modem and uucp since the old days. Way before
my time.

The original authors are:

+ Original cpdate:  "jsloan@wright, 10Dec1986"
+ {cp,mv}note:  pedwards@cs.wright.edu  11Nov1994
+ mvdate:  pedwards@cs.wright.edu  19Nov95
+ Copied to AAMR on W-P AFB, pedwards 22Oct97
+ Merged into one script, date changed from 'ddmmmyy' to
  extended ISO8601 format, added LNCPMV.  pedwards 6Dec1999
+ *time:  added especially for rotlog.  Yes, that 'T' is supposed
  to be there as per 8601.  pedwards 8Dec1999
+ And others who forgot to add their name.

# Note for the 21st centry

This Git repository is an archive of an old Unix/Linux utility that I preserved
for posterity. It dates back to the early days of the internet and was
originally provided to me during my first tech job. I found it in my personal
archive of tools and wanted to share it with others.  — Stefan
