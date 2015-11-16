In this project we have implemented the communication between two servers and many clients, in order to create and application for auctions. 

In order to run the server, first write at a .txt file the information for the items of the auction. The format of this file must be: 
<value of L, in milliseconds>
<number of items (N)>
<initial price of item 1> <description of item 1>
<initial price of item 2> <description of item 2>
.
.
.
<initial price of item N> <description of item N>

This file will be input for the serverLauncher. So, in order to start the servers in two different ports, type: java ServerLauncher <auct_conf.txt>

In order to initiate a client (Bidder) just type: java ClientLauncher <host> <port> <bidderName>

User can type 5 instructions: 

1) i_am_interested: when user sees a new object, then in order to receive feedback or to bid for the object he/she must type the above 

2) quit: the user exits from the application

3) list_high_bid: if user is in the list of interested users for a certain item, he/she will see the current highest bid

4) list_description: if user is in the list of interested users for a certain item, he/she will see the description of the current item being auctioned

5) bid <amount>: places bid for the item 

