# PKI---Configuration-of-HTTPS-in-NGINX

Description 
TLS (Transport Layer Security) and SSL (Secure Socket Layer) are web protocols used to encrypt the traffic between server and client without the possibility of the message being intercepted by third person. The certificate system also assists the users in verifying the identity of the sites that are connected with.
We are going to see how to set up a self-signed SSL certificate for use with a NGINX web server. 

So, what is NGINX?
•	NGINX is a free, open-source, high-performance HTTP server and reverse proxy, as well as an IMAP/POP3 proxy server. 
•	It is known for its high performance, stability, rich feature set, simple configuration, and low resource consumption.
•	Unlike traditional servers, NGINX doesn’t rely on threads to handle requests. Instead it uses a much more scalable event-driven (asynchronous) architecture. 
•	This architecture uses small, but more importantly, predictable amounts of memory under load. Even if you don’t expect to handle thousands of simultaneous requests,      you can still benefit from NGINX’s high-performance and small memory footprint. 
•	NGINX scales in all directions: from the smallest VPS all the way up to large clusters of servers.
