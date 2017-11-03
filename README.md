# tklmon

Shows https://api.vlan.fi/bus/ data more beatifully.

Usage

	tklmon/?stop=1234&param1=XYZ

Possible parameters are at the moment:

	stop: stop number according to http://joukkoliikenne.tampere.fi/
	lines: dot separated list of line numbers to show
	bg: background color (eg. blue, rgb(1,2,3))
	fg: foreground color = text color
	interval: how often data is retrieved (given in seconds, default is 1min)
	clock=no: hide clock
	showage=yes: show age of data (api gives age of the cached data)
