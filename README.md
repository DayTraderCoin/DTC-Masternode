
DaytraderCoin development tree

DaytraderCoin is a PoS-based cryptocurrency.

DTC is dependent upon libsecp256k1 by sipa, the sources for which can be found here:
https://github.com/bitcoin/secp256k1

POS Reward: 30 DTC
Block Spacing: 60 Seconds
Diff Retarget: 10 Blocks
Maturity: 20 Blocks
Stake Minimum Age: 24 Hours

40 MegaByte Maximum Block Size (40X Bitcoin Core)


Mainnet
Default Port = 37246
RPC Port = 37245

Testnet
Default Port = 55555
RPC Port = 20115

Magic Bytes: 0xf1 0xac 0xa1 0xc7

DTC includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the DTC codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument.  It may take 10-15 minutes to build the initial index.

DaytraderCoin has an estimated transaction volume of 12,372.578 TX/s.

Bandwidth Requirements:
Down: 	22.37Mbps
Up: 	156.587Mbps

Disk Requirements:
Data Cap : 14TB/month
Disk Capacity : 21.1TB per year

Original Block Distribution

block 155k: PoS: 200 (30% staker (60) / 55% masternode (110) / 15% team (30) )
block 175k: PoS: 160 (30% staker (48) / 60% masternode (96) / 10% team (16) )
block 200k: PoS: 100 (25% staker (25) / 65% masternode (65) / 10% team (10) )
from block 200k: 12.5% halving (exponential, so 90%, 81%, 72.9%...) every 100k blocks
