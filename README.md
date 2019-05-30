# Mining-cards-to-Gtx-easy-conversion-method
Having seen many video tutorials of modded drivers and searching over the vast www  , this is actually the easiest way to work a mining card as a gpu for gaming purpose
 You don't need to modify the driver, just download 417.22 drivers from online repository , not nvidia site due to them patching their drivers 
 then open Registry and search for AdapterType 
 or go to this destination and try looking for AdapterType in one of the folders (000, 001, 002..etc) 
Computer\HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control\Class\{4d36e968-e325-11ce-bfc1-08002be10318}\
now just double click on AdapterType and change it to 4 and hit ok.
Then below it, you will find EnableMsHybrid double click on it and change it to 1 instead of 0, hit ok
reboot the pc and then open Nvidia control panel and make the P106  the default GPU and you are set to go.
IMPORTANT IS TO RUN REGISTRY FILE PROVIDED HERE TO DISABLE AUTOMATIC WINDOWS DRIVER UPDATE IN ORDER TO AVOID REINSTALL FROM SCRATCH FROM YOUR SETUP DRIVERS
