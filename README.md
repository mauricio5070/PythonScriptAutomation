# PythonScriptAutomation
Python code to automate the way security solution´s bundle was sent to printers through the CMD.
This Script uses regular expresions to read the IPs from a txt file and replace the IP on the scrip for copy, paste and run on the CMD.

Utilitie's operationas and parameter:

Operations:

  -i or --install        Install or upgrade a bundle - may restart the device!
  -g or --getconfig      Download the configuration XML file from a device
  -s or --setconfig      Upload the configuration XML file to a device

Parameters:

  -d or --device         Device type (HP, CANON, RICOH, SAMSUNG)
  -a or --address        Device IP address
  -u or --user           Device administrator username
  -p or --password       Device administrator password
  -c or --community      SNMP community name of device
  -f or --file           File name (bundle or config XML)
  -v or --serveraddress  Safecom G4 server address (default is 127.0.0.1)
  -w or --adminuser      Safecom administrator logon name (mandatory)
  -x or --adminpassword  Safecom administrator password (mandatory)
  
  scDevUtilConsole.exe --install --device HP --address IP --user admin --password passwordgoeshere --community communitynamegoeshere --file 31005032.b95 --serveraddress ipserver --adminuser admin --adminpassword adminpasswordgoeshere

