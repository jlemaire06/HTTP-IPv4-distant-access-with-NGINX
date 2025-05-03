# HTTP-IPv4-distant-access-with-NGINX
Here we propose to show how we can resolve the distant access problem to an HTTP-IPV4 server located on a local network, by activating the "reverse proxy" functionality of the NGINX server, launched as an OpenWrt service on an IPV4-IPV6 router, which defines this local network. 
Access will be made in IPv6, using the IPv6 public fixed address allocated to this router by an Internet fiber box, IPV4-IPV6, operating in IPV4 CGNAT, therefore without IPV4 public address. 
This study was motivated by remotely piloting a photovoltaic installation.
