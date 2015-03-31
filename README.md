# dsn-idea
Just another distributed social network idea (just some thoughts)

##Main idea
The webclient retrieves all posts of other users(friends), independent from its source server and merges them in a microblogging feed.

##Authentication
Each user stores a keyring (similar to a web of trust). If a user adds a new friend they will exchange there keys.

##Why not P2P?
If a peer is offline he can't share posts with his friends. You could cache them some where on the internet but you had still no p2p network. (I now there are other possibility too). Also if your online you have still a slow upload speed (ad least on my end :() 

##Friend lookup
One of the more complex part is to find friends and on witch server they are.
