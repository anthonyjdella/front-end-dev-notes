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

* Rendering engine will parse HTML to construct the DOM tree. Then parse CSS to construct a CSSOM tree. Then both will be merged into a render tree. Then that will become a layout tree, finally it will be "painted" to the page.

# DNS
* If your browser can't find an IP address that's been cached, it will send a query to the Resolving Name Server (handled by ISP) for the IP Address. The RNS will locate the Root Server which knows where to find .com, .org, etc. Then that will query the Top Level Domain Server, or Authoritative Name Server, with help from the Registrar (where the domain is registered). The IP Address from the Domain Level Name Server will now be found.

# HTTP
* Within the 4 layers of TCP/IP, HTTP is the top layer (application layer). So although things go from client to server, routers and modems are in between them (on different layers).

* A server isn't always one computer, it can be many.

* Requests consist of method (GET, POST), path (/...), version of protocol (HTTP 1.1 or 2.0), and Headers (additional info). A body is present for POST requests because those are used for things like sending data from HTML forms.

* Responses consist of version (HTTP 1.1 or 2.0), status code (200 or 404), status message (OK), and Headers. And sometimes a body containing the fetched resource.

* 1xx status codes are information, 2xx are success, 3xx are redirection, 4xx are client side errors, 5xx are server side errors.