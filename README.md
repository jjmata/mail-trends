Mail Trends
====

Mail Trends lets you analyze and visualize your email (as extracted from an IMAP server). You can see:

* Distribution of messages by year, month, day, day of week and time of day. 
* Distribution of messages by size and your top 40 largest messages
* The top senders, recipients and mailing lists you're on.
* Distributions of senders, recipients and mailing lists over time
* The distribution of thread lengths and the lists and people that result in the longest threads

This package was modified from the original in order to fix some errors and to add support for a larger amount of servers, and email origins. 

In particular, the mail-trends will scan for all mailboxes and present global stats.

For GMAIL, it may produce duplicate stats unless you filter results to only consider the "All Mail" folder.

For the original version, please see: http://code.google.com/p/mail-trends/

Original Copyright Mihai Parparita
modified by Joao Paulo Barraca <jpbarraca@ua.pt>


Example usage:

./main.py --server=mail.domain.com --username=guest --password=1234 --use_ssl
python main.py --server=mail.pynsa.es --username=prueba@pynsa.es --me=prueba@pynsa.es

or reading a local Maildir folder

./main.py --maildir=~/Mail


