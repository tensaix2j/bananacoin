
My altcoin experiment!
=====================


To compile:
	make -f makefile.unix 

To Build, Required libs are:
	build-essential
	libssl-dev
	libboost-all-dev
	libdb++-dev
	libqt4-dev
	libminiupnpc-dev




bananacoin.conf to start mining:
	rpcuser=anyname
 	rpcpassword=anypassword
	gen=1
	listen=1

	addnode=<peer ip>
	connect=<peer ip>


To run:
	bananacoind --daemon
  


