Birdwallet integration/staging tree Development
================================

Copyright (c) 2009-2018 Bitcoin Developers
Copyright (c) 2017-2018 TTcoin Developers
Copyright (c) 2023 Birdwallet Developers

What is Birdwallet?
----------------

Birdwallet is a lite version of Bitcoin using scrypt as a proof-of-work algorithm(to be changed to poof of trends on twitter)
All specification to be reoganized in order of
1. Getwork = Gettrends
2. Gettrends=specific twitter id
3. specific twitter id = gethash
4. gethash = genblock
5. genblock = gethash
6. gethash = specific twitter id
7. specific twitter id = create wallet

// - 2.5 minute block targets
 - subsidy halves in 840k blocks (~4 years)
 - ~84 million total coins

The rest is the same as Bitcoin.
 - 50 coins per block
 - 2016 blocks to retarget difficulty
//
For more information, as well as an immediately useable, binary version of
the TTcoin client sofware, see http://www.TTcoin.org.

License
-------

Birdwallet is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the TTcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/TTcoin-project/TTcoin/tags) are created
regularly to indicate new official, stable release versions of TTcoin.



