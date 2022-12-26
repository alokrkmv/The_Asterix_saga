# The_Asterix_saga

### This is a filler repository for labs under compsci-677 (Distributed and Operating System) at Umass Amherst for fall 2022.

#### Lab-1 Asterix and the Bazaar

#### Problem Statement

Construct a p2p network such that all N peers form a connected network. You can use either a structured or unstructured P2P topology to construct the network. All peers should have no more than three direct neighbors, and should only communicate directly (make RPCs, RMIs, or use the sockets
of) direct neighbors during the simulation. You should also ensure that the network is fully connected: Once the network is formed, assign each peer a random role: fish seller, salt seller, boar seller, or buyer. Once the roles have been assigned, each buyer randomly picks an item and attempts to
purchase it using certain interfaces specified below; it then waits a random amount of time, then picks another thing to buy, and so on. Each seller starts with n items (e.g., n boars) to sell; upon selling all n items, the seller picks another thing at random and becomes a seller of that item.

#### Lab 1 URL : ![Asterix and the Bazaar](https://github.com/alokrkmv/lab-1-the_bazar)


#### Lab-2 Asterix and the Trading Post

#### Problem Statement

Construct a p2p network such that all N peers form a connected network. You can use either a structured or unstructured P2P topology to construct the network. All peers should have no more than three direct neighbors, and should only communicate directly (make RPCs, RMIs, or use the sockets of) direct neighbors during the simulation. You should also ensure that the network is fully connected: Once the network is formed, assign each peer a random role: fish seller, salt seller, boar seller, or buyer. Once the network is formed peers will do a leader election and elect a trader. After a trader is successfully elected all sellers will deposit their items to the trader. Buyers can only purchase items directly from the trader. To make the trade fair, traders will resolve the buy request and pick the seller based on logical clocks like the Lamport clock or vector clock. A trader will also maintain meticulous documentation of the status of the bazaar to make sure that the system is fault tolerance.

#### Lab 2 URL : ![Asterix and the Trading Post](https://github.com/alokrkmv/lab-2-the_trading_post)

#### Lab-3 Asterix and Multi-Trader Trouble

#### Problem Statement

Construct a p2p network such that all N peers form a connected network. You can use either a structured or unstructured P2P topology to construct the network. All peers should have no more than three direct neighbors, and should only communicate directly (make RPCs, RMIs, or use the sockets of) direct neighbors during the simulation. You should also ensure that the network is fully connected: Once the network is formed, assign each peer a random role: fish seller, salt seller, boar seller, or buyer. Once the network is formed peers will do a leader election and elect a trader. After a trader is successfully elected all sellers will deposit their items to the trader. Buyers can only purchase items directly from the trader. Unlike in lab 2 in this lab there can be mutliple traders in the bazaar and buyers and sellers can choose one trader at random to send their buy and sell request. A trader will keep meticulous account of the whole bazaar both in a database and a cache layer. Make sure that the cache is consistent. You can use any non-strict cache consistency algorithm.

#### Lab 3 URL : ![Asterix and the Multi Treader trouble](https://github.com/alokrkmv/lab_3_cache_consistency)


