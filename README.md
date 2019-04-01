# Internet
* The internet is a distributed (not central) system of interconnected computer networks that use TCP/IP (communication protocols/set of rules) to link devices. The Internet is the network that makes computers communicate together. Internet is the infrastructure, Web is the service (Internet is parent).

* TCP/IP is a protocol that helps data go from text to electronic signals to transmit over the Internet and back into text. TCP deals with port numbers (allowing you to multitask because each application, like browser and email client, uses a different port). TCP makes sure packets arrive and are in the correct order. IP is a protocol to send packets to other computers based on the IP address.

* Data sent over the Internet are in bits (0s and 1s) as binary code. The maximum amount of bits sent due to a device's capacity is called bandwidth. Latency is how fast a data packet can travel from point A to point B.

* My network -> router -> modem -> ISP -> destination ISP -> destination modem -> destination router -> destination network
    
* A router, routes data to a specific location, rather than multiple computers accessing eachother at the same time. Instead of having one computer send and receive many requests, that request is sent to a router to handle, which then routes it to the destination.

* A modem, allows your network to connect to other networks. This is done over telephone wires/infrastructure.

* An ISP is linked to other ISPs and helps route our destination.

* IP address is a unique identifier of an address (web site or computer).

* Domain name is the alias of an IP address that makes it human readable (e.g google.com)

* DNS is like an address book that will look up the domain name with the corresponding IP address.

# Web
* Clients (request) and servers (response) are what make up the Web.

* Clients are the device and servers are the computer that store the webpages.

* Browser -> DNS -> IP address -> HTTP request -> HTTP response 

* HTTP is a protocol that defines how clients and servers speak to eachother (methods like GET, POST).

* SSL and TLS are security protocols that make data secure on the Web. They are the lock on a web browser with a certificate that the site is safe.

# Browser
* Browsers have the following components: user interface, browser engine, rendering engine, networking, Javascript interpreter, ui backend, & data storage (for cookies).

* Chrome uses V8 as its Javascript interpreter and Blink as its browser engine.

* Rendering engine will parse HTML to construct the DOM tree. Then parse CSS to construct a render tree. Then map the two trees together to "paint" the page.