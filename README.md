# Float_Servers
In this project we desired to write servers, which can handle computations regarding sequences.

# User instructions
The code comes with 3 similar servers. All of them offer the same sequences (but with different names), they only differ in their names. The original server's name is Binarni Banditi, the second one is named Binarni Banditi & AmondUs and the third one is names Binarni Banditi & Elves. To use these servers, first run the register, then run all of the main.rs files in the three generator folders. Then you can send requests via the try.py file. There are some test in this script, so when you run it some tests will execute and will let you know if everything is working as it should. Then you can alter the requests in the python script to send other (more complex) sequences to these servers.

# How the family of servers works


# Server's capabilities
The server offers some basic capabilities such as responding to /ping requests, /sequence requests, which gives the user the list of sequences available on the server. The main functionality comes from the POST requests. With a POST you may request some elements of some sequence from the server, following the examples from the python script. 
