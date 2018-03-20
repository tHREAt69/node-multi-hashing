node-multi-hashing
===============
Cryptocurrency hashing functions for [Node Stratum Pool](https://github.com/foxer666/node-stratum-pool)

Recent Updates:
* March 19th, 2018
  * Enabled the Yescrypt, YescryptR16 and YescryptR32 algorithma. Currently testing R32 using Wavi, shares work.
  * C11 is now confirmed working with shares/payout using Dixicoin.
* March 10th, 2018
  * Enabled the c11 algorithm. Currently testing using the Dixicoin testnet.

Need testing for blake algos, we have modified sph_blake.c with fresh version to make lyra2z is working right. Need tests to be sure nothing else is broken.

Current version v1.0.2
