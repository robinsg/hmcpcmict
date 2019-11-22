# hmcpcmict
ICT specific nextract_server and hmc_pcm
Based on hmc_pcm.py V10

1. Removed the need to import InfluxDB as we don't need it
2. Auto creates the debug folder if it doesn't exist
3. If debug is off in both nextract_server.py and hmc_pcm.py, remove *.JSON, *.json, *.XML, *.xml  and Stats--* files from the debug folder
4. Added OS detection so that the correct command for cleaning up the debug folder are used
