time-tracker
============

Very simple time tracker

Usage:
./tt -w your_action

and when finished, close the terminal or Ctrl+C

version 1.2.0

Example:

	n@t:~/Dropbox/time-tracker$ ./tt -v -g 08:00:00 -w BI-SZZ
	action: BI-SZZ
	today: 03:20:41
	since: 18:50:19
	elapsed: 00:00:02 total: 03:20:43 goal in: 04:39:17^C
	This track has been logged!

- 1.1.0 changelog: added -v for verbose information.
without this parameter just print time

- 1.2.0 changelog: added -g HH:MM:SS to add time goal
