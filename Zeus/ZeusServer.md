# The Zeus Server

The Zeus Server is currently on a single Raspberry Pi 4B.

## Technology

### Raspberry Pi 4B

The Raspberry Pi 4B is a mini computer with 8 Gigabytes of RAM. I chose it as the appropriate
hardware for this project as I had one laying around and wanted to use it to its full potential.
I recognize that the server system may need to become more robust with the addition of more projects
that live on the Zeus network, and I am looking forward to learning about a multi-server setup with
either more Raspberry Pi 4B's or having multiple weaker computers that can handle smaller loads.

### Apache

The Apache server was interesting to set up. It was really simple after following a tutorial. I learned
how to setup VirtualHosts, and have custom domains on the server along with IP mapping. I particularly
like the folder structure of Apache and how you can have a clean hierarchy of projects as long as they
are located in the /var/www directory.

### dnsmasq

Although I consider myself a "web-developer" I learned a lot about DNS through this project. It had not
really occurred to me that every machine's IP address had to have a domain mapping that acts almost like
a phonebook. Setting up IP mapping for my own custom domains was really fun and some brainstorming took
place before I settled on "Zeus" as the final name.

## Challenges

### DNS

This stuff is relatively dated and since this is the case, finding tutorials and documentation was
relatively difficult since it was at a lower level that what I'm used to, and also I was learning
something new. But after asking a friend for help and reading more about the philosophy of networking,
things began to click and it got much easier.
