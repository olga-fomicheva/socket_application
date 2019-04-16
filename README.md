Application "socket" is made for a study purpose; it contains a very simple socket-based web application with comments. 

It illustrates how socket and routing flow work in Django and Flask.

Here you can find a link for the lesson I followed while coding:

https://www.youtube.com/watch?v=4haMUvUxUJI

Some basic descriptions:
 
1. HTTP (hypertext transfer protocol) is based on two protocols: TCP and IP. HTTP has the highest level of abstraction.

2. IP (internet protocol) has the lowest abstraction level. Thanks to IP data transfer tunnel is created between the two hosts/machines.

Data is transmitted in packages. Unfortunately, the IP protocol is very unreliable. Packages can be sent in the wrong order, may be damaged, lost or duplicated. 

IP protocol defines an IP address.

3. TCP (transmission control protocol) - TCP provides reliable, ordered, and error-checked delivery of packages.

TCP is using a transmission port. Ports are allowing multiple applications to use TCP on the same machine without occupying the whole tunnel.

TCP's level of abstraction is higher than IP's.  

A pair of IP address and port is called a socket address. Sockets can be server and client.