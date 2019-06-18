TMA is the first distributed ledger, which implements full sharding. Currently, it consists of 8 blockchains, which are collectively merge mined. For example, shard 0 collects hashes from shards 1, 3, 7 and shard 1 collects hashes from shards 0, 2, 6 for merge mining. When network grows to over a million shards (2^20) then a single shards would need to merge mine just 20 other hashes.
It will start splitting into more shards as more nodes join the network.

Installation instructions

1)    Install latest Java JDK, later than 1.8.0_172, since older version might have some problem with cryptography strength; Java 64 bit works faster.
2)    Download the Application: go to https://github.com/tmacoin/tma and select download zip. Unzip it into folder where you have full access rights.
3)    When starting TMA for the first time, it will download blocks until the current block. To speed this process, another option is avaiable. Use the following link https://drive.google.com/open?id=1fhvBgXA7mG2w9a9KIadAo9Mg2GJFuQN3 to download one of the data zip files; that is, select a random blockchain(zip file) data. By selecting a random zip file, it will distribute nodes evenly between shards. After you download and unzip the zip file, go to(i.e. cd) to the /data folder. The derbydb directory should exist immediatley below the /data directory. The /data folder should be located in the same directory as tma.bat/tma.sh.  Getting the data directory structure is imperative, since tma.bat, tmagui.bat or tma.sh point to "data/" folder when starting the app.     
      note:  If using 7-zip, "select Extract Here" when unzipping the data.zip file.
4)    Configure your firewall to accept incoming connections. It should allow incoming traffic on port 4000.
5)    To start the app, double click on either tma.bat or tmagui.bat and enter your passphrase and confirm passphras. DO NOT FORGET YOUR PASSPHRASE. Currently, tmagui.bat only works on Windows. Note: no one can assist you with restoring your passphrase, so store it in a safe place, preferable cold storage(off the Internet).
6)    To verify the application is executing, check tma.log file in log directory, which exist in the TMA master diretory. File tma.sh works on Linux without GUI. Tested nongui on Macintosh, Ubuntu and Solaris.
7)    Finally, in order to start mining, a minimum balance of one coin is required.
8)    Currently when sending coins, transaction fee is optional and can be set to 0

Please check message board at https://cointma.org for more information.

June 16, 2019: latest release is 0.0.8. Removed certain changes that caused instability. To upgrade from release 0.0.7 just: 
      1) Shutdown your instance by executing the shutdown script or File|Exit menu
      2) Download/replace tma.jar
      3) Restart the app by executing tma.* script

May 14, 2019: Release 0.0.7. New algorithm to achive consensus between shards. To upgrade from release 0.0.6 just replace tma.jar and restart the app.
