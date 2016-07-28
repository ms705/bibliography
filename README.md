Computer Systems bibliography
=============================

This repository contains BibTeX/Biber bibliography files covering (roughly)
computer systems research. I use these files as my "master" bibliography
files, rather than having per-project ad-hoc bibliographies, because I have
curated them over the years to follow a consistent style.

These files are unlikely to be super useful to anyone else, but if you do
want to use them, note the following:

 * For named systems, I use the system name in lower case (e.g., "unix" or
   "quincy") as the citation key.

 * The `booktitle` field for conference proceedings follows a convention of
   putting the numbered instance of the conference with a superscript (e.g.,
   "25\textsuperscript{th}") where available, having the full conference
   name (e.g., "Symposium on Operating Systems Principles") followed by the
   shorthand in parentheses at the end (e.g., "(SOSP)"). There are some
   conferences whose official names do not follow this structure (e.g.,
   SIGCOMM, SIGMOD), and I use a different format for them.

 * All entries have both `year` and `month` to date them, unless I couldn't
   find out when the item was published (quite rare).

 * All conference paper entries have the full location of the conference
   specified in the `location` field, with a format of "City, State,
   Country" (e.g., "Boston, Massachussetts, USA", or "London, England, UK").
   Not all conferences are in the US, so "Boston, MA" isn't sufficient or
   consistent :-)

 * I generally remove the `address` and `series` fields.

 * Technical reports and URLs often have a `note` field containing a
   specification of when I accessed them.
