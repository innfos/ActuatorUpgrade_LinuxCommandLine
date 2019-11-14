# ActuatorUpgrade_LinuxCommandLine
Upgrade Innfos Actuator with Linux command line.

For commandline: 
-r: read all connected Innfos Actuator. 
./ActuatorUpgrade -r

-id + Actuator number + filepath: upgrade designated actuator.
./ActuatorUpgrade -id 2 /home/2.txt

-all + filedirectory: Put the upgrade file in the directroy,Upgrade all actuator.
./Actuator -all /home/  
