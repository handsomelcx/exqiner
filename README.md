# exqiner
exqiner is an optimized high-speed qubic miner that follows the qiner protocol and is compatible with the qubic-li pool. exqiner has suitable dev fee, higher hashrate and earnings.

# hashrate
* 4090    1400 it/s
* 3090    723 it/s
* 3080    489 it/s

# one command to run 
`wget -c https://github.com/exminer/exqiner/releases/download/v0.1.0/onecommandrun.sh; bash onecommandrun.sh YourLiAccesstoken`

# Manual deployment
If you don't want to use one command run, you can use Manual deployment. Download qli-client https://dl.qubic.li/downloads/qli-Client-1.8.10-Linux-x64.tar.gz ,If you already have it, it is recommended to use version 1.8.10. Download exqiner from release, put it in the qli-Client directory. Fill the Accesstoken in the appsettings.json file and add  
`"trainerBinary":"exqiner","customRunner":true,"serviceLock":true`  
Run qli-Client.  

The screen refreshes once a minute
