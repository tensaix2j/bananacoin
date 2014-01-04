My altcoin experiment!
=====================


To compile:

	make -f makefile.unix 



Required libs:

	build-essential

	libssl-dev

	libboost-all-dev

	libdb++-dev

	libqt4-dev

	libminiupnpc-dev




bananacoin.conf:

	rpcuser=anyname

 	rpcpassword=anypassword

	gen=1

	listen=1

	addnode=<peer ip>

	connect=<peer ip>


Run as daemon:

	bananacoind --daemon
  


