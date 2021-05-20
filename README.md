# chiasync
Simple batch files that sync Chia (1.1.5) 

Very simple to operate.  Contains two batch files that you need to modify to your user name and current Chia app version and then put them in the correct folder.  All of the nodes were updated 5/20/2021 via https://chia.powerlayout.com/ filtering only the USA nodes.  If you are not in the USA, then you will want to update the node IPs for optimum connections. 

1) nodes.bat  -  place this inside of your Chia Daemon folder:

      -->  C:\Users\YOUR_USER_NAME_GOES_HERE\AppData\Local\chia-blockchain\app-1.1.5\resources\app.asar.unpacked\daemon
      
      -->  Note:  If you are not using 1.1.5 then change the app directory here ^^^

2) start_nodes.bat - place this on your desktop and double click it to perform the sync

      -->  Change the file directory and App to match the location of the nodes.bat file
      
      -->  C:\Users\YOUR_USER_NAME_GOES_HERE\AppData\Local\chia-blockchain\app-1.1.5\resources\app.asar.unpacked\daemon
      
After both batches are updated, double cliick the "nodes.bat" file and your Chia sync issues will disappear.
