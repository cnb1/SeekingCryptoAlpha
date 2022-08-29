# SeekingCryptoAlpha
Contains the webapp and the backend algorithmic trading repo.


-----------------------------------------------------------------------------------------------
ToDo
- need only one price thread there shouldnt be more than one
	- this will require the price thread to get kicked off when there
	is atleast one user trading
	- when this single price thread gets kicked off when 1 user is started or ended when no more users are trading
	- when it is kicked off it will send a price that was grabbed to
	the designed users map
	1. when a price is grabbed then it forloops through the users
	2. for each active trading user then add a price to that channel
	3. get rid of the multiple price grabbing threads so that only
		one will exists at any given time
- how to get post return value
- when its starting then we need to have a stop trading button
- create a get price button that requests directly to the program
- when you stop have the mongo db program update the document in the database for total amt
