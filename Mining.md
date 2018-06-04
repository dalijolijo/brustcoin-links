# BURST Mining

## Hardware
* 

## Software

### Operating System
* Linux (Ubuntu 16.04)

### Mining Software for Linux (CPU)
* Burstcoin C++ CPU and GPU Miner "creepminer": https://github.com/Creepsky/creepMiner/releases

## Mining Pools
* List of all pools supporting the hard fork: https://ecomine.earth/burstpools
* Burst PoCC Pools (0-100 / 50-50 / 100-0): https://burst.cryptoguru.org

### Mining Pools Choice
Depending on the mining capacity select one of the following pools (see https://www.ecomine.earth/burstpools)
* 0-100 Pool: 0% for the block finder, 100% historic. This pool is suited for small miner sizes up to 30TB rigs.
* 50-50 Pool: 50% for the block finder, 50% historic. This pool is suited for medium miner sizes with 30TB to 250TB mining rigs.
* 100-0 Pool: 100% for the block finder, 0% historic. This is the "solo miner" pool for large mining rigs > 250TB.

### Pool Mining Hits
* Check fees
* Check max. acceped deadline (DL)
* Use of correct Pool type (0-100 / 50-50 / 100-0)
* Use Telegram Bot for Burst PoCC 0-100 Pool @CGBurstPP_0_100_Bot


## Mining Procedure Tips

### Read Time
#### What is the max. acceptable read time for mining?
* Max. read time is 1 minute
* Read time for BEST Performance <30 seconds

#### How can read time be improved? Which hardware components should I pay attention to?
* CPU threads: 1 per drive best. up to 3 drives per thread acceptable
* RAM capacity: enough to run OS + 2 GB
* HDD technology: cheapest to provide greatest space
* HDD capacity: as much as possible
* HDD interface (SAS or SATA): both good, hard drive cannot saturate, does not matter
* RAID: not needed, not of use
* Controller specification (e.g. internal RAM)

#### In which way should I connect SATA or SAS drives?
* Directly to board or a JBOD controller is best

