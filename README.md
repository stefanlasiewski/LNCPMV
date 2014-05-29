LNCPMV
======

LNCPMV - {ln,cp,mv}{date,note,time}

{LNCPMV,"{cp,mv}{date,note,time} {args}"}

Use a single uility to link, copy or move a file with an extension based on the date, a note or the time.

If called as LNCPMV, creates the files listed in LIST below as hardlinks.

# Usage:

./LNCPMV -- Will create the following hardlink

LNCPV   -- This utilityu
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

# Credits

This is an ancient script from the Public Domain. The original authors are:

# +  Original cpdate:  "jsloan@wright, 10Dec1986"
# +  {cp,mv}note:  pedwards@cs.wright.edu  11Nov1994
# +  mvdate:  pedwards@cs.wright.edu  19Nov95
# +  Copied to AAMR on W-P AFB, pedwards 22Oct97
# +  Merged into one script, date changed from 'ddmmmyy' to
#    extended ISO8601 format, added LNCPMV.  pedwards 6Dec1999
# +  *time:  added especially for rotlog.  Yes, that 'T' is supposed
#    to be there as per 8601.  pedwards 8Dec1999
