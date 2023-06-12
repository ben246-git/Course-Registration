# Course-Registration-System
The program is a registration system at BG University. focused on communication between tasks. The communication between the server and the client(s) will be performed by two protocols: 
1. Thread-Per-Client (TPC)  
2. Reactor servers. 

Testing run commands:

For reactor server protocol:

mvn exec:java -Dexec.mainClass=”bgu.spl.net.impl.BGRSServer.ReactorMain” - Dexec.args=”<port> <Num of threads>”

For thread per client server:

mvn exec:java -Dexec.mainClass=”bgu.spl.net.impl.BGRSServer.TPCMain” - Dexec.args=”<port>”

After than :
  
make: BGRSclient <ip> <port> 



