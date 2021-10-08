# gpsd2traccar

Report GPS positions from gpsd to a traccar server using the osmand protocol.

This is a quick and dirty python2 script that reports GPS fixes to a traccar server. It can run as a daemon.
I did not find something like this anywhere, so I rolled my own. 
No claims to elegance or efficiency whatsoever.
At best I expect people to use it as a basis for their own application.

Configuration is done by reasonably well described settings at the top of the script. 
The minimum you need to set are the URL of your traccar server and the traccar ID.

'Full' reports are an example how to periodically include other vehicle data. 
Unless you just happen to have a Victron BMV battery monitor connected via FHEM
you will have to roll your own there ;-)

Constructive critisim welcome. Let me know if you do a python3 version 
or a more modern gpsd interface. 
