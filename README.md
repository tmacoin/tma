TMA is the first distributed ledger, which implements full sharding. Currently, it consists of 8 blockchains, which are collectively merge mined. It will start splitting into more shards as more nodes join the network.

Installation instructions

1)    Install latest Java JDK, later than 1.8.0_172, since older version might have some problem with cryptography strength. Java 64 bit works faster.
2)    Download the Application: go to https://github.com/tmacoin/tma and select download zip. Unzip it into folder where you have full access.
3)    Double click on either tma.bat or tmagui.bat and enter passphrase that you will not forget. tmagui.bat only works on Windows. Note: no one can assist you with restoring your passphrase, so store it in a safe place!
4)    To verify the application is executing, check tma.log file in log directory. tma.sh works on Linux without GUI. Tested nongui on Macintosh, Ubuntu and Solaris.
5)    When starting TMA for the first time, it will download blocks until the current block. However, there is another option. To speed-up the initial start-up, use the following link https://drive.google.com/open?id=1fhvBgXA7mG2w9a9KIadAo9Mg2GJFuQN3 and download one of 8 blockchains. Select a random blockchain to distribute nodes evenly between shards. In order to accept incoming connections firewall/router should allow incoming traffic on port 4000.
6)    Finally, in order to start mining, a minimum balance of one coin is required.

Please check message board at https://cointma.org for more information