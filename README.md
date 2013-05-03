Junkcoin - a fork of Litecoin version with random bonus blocks. Like Litecoin it uses scrypt as a proof of work scheme.

	- Total coins will be around 54 millions
	- Mining will be shut down after 12 years.
	- 2 minutes block target
	- Difficulty retargets once per day
	- To encorage early adoption the coins per block is high for the first 4 days:
		- 1st day: 500 coins per block
		- 2nd day: 200 coins per block
		- 3rd/4th days: 100 coins per block
	- Starting 5th day, it will be 50 coins per block, will be halved every two years (or 518400 blocks).
	- In regular mining (after first 4 bonus days), there will be 1% chance a block will yield triple of the normal coins (e.g. in the first 2 years there's 1% chance you get 150 coins per block).
	- There is also 1/10,000 (0.01%) chance that a block will yield 1000 coins. This is valid for all 12 years of the mining.
	- The default ports are 9771(connect) and 9772(json rpc).


Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Litecoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'. 
