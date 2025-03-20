# Networking and OS Portfolio
Eportfolio for Networking and OS module

# NOS Week 2
Python Fundamentals

The TA told me to start at exercize 6, the password checker. I did this, used flags to check if the password is valid, and refactored my code so error messages would always fit.
Ceaser Cipher and Hangman were pretty straightforward to make. 

See included ipynb file named after this week.

# NOS Week 3
Application Layer in Networks

We started by getting the IP address from a website, then used tracert to trace the network route packages take. It wasn't very illuminating until we used our own wifi.

Exercize 1: I did this for multiple websites
Exercize 2: I did this also for multiple sites
Exercize 3: Once I stopped using Eduroam, my output did look like that. Over repeated traces, it got faster.
Exercize 4: There were some connections which timed out or took a very long time, but over repeated traces this improved.
Exercize 5: I wasn't able to change my location effectively in the lab.

We built an HTTP client to fetch data, then used requests to do so much easier.

Finally we used HTTP Requests to POST, PUT, and DELETE data.

See included ipynb file named after this week.

# NOS Week 4
Transport Layer in Networks

We made a UDP Server and Client, and made it so they could speak together. We then added a dictionary with the user's IP address, and added authentication.

See included server and client ipynb files named after this week.

# NOS Week 5
Transport Layer Part 2

We made a TCP server and client, and made it so they could speak together. We then timed how long this took and compared it to UDP (which was faster).
We made a log file which was quite difficult to get it so it would actually write to the file, I had some issues with the cache if I remember right.
In the end I was able to send files correctly, a few words took 0.0000 seconds to send, a paragraph took 0.0008 seconds.
In UDP it took 0.0020 to send a few words or a thousand.

See included server and client ipynb files named after this week.

# NOS Week 6
Internet Layer

This lab we analyzed our IPs, mine is private, and the details are:
Network: 192.168.172.0/24
Netmask: 255.255.255.0
Broadcast Address: 192.168.172.255
First Usable Host: 192.168.172.1
Last Usable Host: 192.168.172.254
Number of Usable Hosts: 254

We then used the week 3 lab to get the IP address of Goldsmiths, which is public:
Network: 184.85.56.78/32
Netmask: 255.255.255.255
Broadcast Address: 184.85.56.78
First Usable Host: None
Last Usable Host: None
Number of Usable Hosts: 0

Department: Engineering
Subnet: 172.16.0.0/27
Usable IP Range: 172.16.0.1 - 172.16.0.30
Broadcast Address: 172.16.0.31
Number of Usable Hosts: 30

Department: Marketing
Subnet: 172.16.0.32/27
Usable IP Range: 172.16.0.33 - 172.16.0.62
Broadcast Address: 172.16.0.63
Number of Usable Hosts: 30

Department: Finance
Subnet: 172.16.0.64/28
Usable IP Range: 172.16.0.65 - 172.16.0.78
Broadcast Address: 172.16.0.79
Number of Usable Hosts: 14

Department: HR
Subnet: 172.16.0.80/29
Usable IP Range: 172.16.0.81 - 172.16.0.86
Broadcast Address: 172.16.0.87
Number of Usable Hosts: 6

See included server and client ipynb files named after this week.

# NOS Week 7
Network Access Layer

We simulated single bit parity checks and two dimensional parity check
We simulated errors, and how they can be resolved
We used ones complement to caluclate and verify checksums
We graphed the efficiency of slotted Aloha

See included server and client ipynb files named after this week.
