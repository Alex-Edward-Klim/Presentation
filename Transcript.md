Ladies and gentlemen!


Despite the fact that the name of this topic may seem pretty easy, don’t let it fool you! Even these days some web developers (I repeat: WEB DEVELOPERS!) can shock us, because some of them do naively think that buying more bandwidth will solve their problems with live streaming on YouTube; or they absurdly believe that satellite Internet is the fastest one… What a nonsense!?


So the main goal of this presentation is to put you into top 10% of web developers who do really know and clearly understand the main concepts of how the Internet works. Of course, the time frame of this presentation doesn’t allow me to go deeper into all the details, but I’ll try to do my best to touch upon every important thing on this topic.


Let’s get started!


The word ‘Internet’ itself means ‘interconnected network’. Computers can be connected together via different ways: cables, satellites, cellular towers and so on. But what is so special about the Internet? The main edge where this technology really shines lays out in its indestructibility: this form of communication and interaction between computers is almost NOT able to be destroyed. Why? Because, first of all, we should remember that this technology was being created as a military technology! For example, if someone takes scissors and just cuts a wire, then computers must NOT lose connection between each other! And how did they do that!? The general idea is pretty simple: to organize the whole computer network like a spider web with many-many different routes (like roads on a city map). For example, if we take a look at a map of any city, and you need to get from one point to the other point, you will see that there is a plenty of different ways to get to your point. And if some roads are closed or terrible traffic jam happens, you can always find a detour, use other streets and get to the destination point. So the Internet works on the same principle: if some routes are destroyed or blocked or shut down, there will always be a detour (another route) to the target computer.


There is one more important thing to mention: despite the fact that there are many different routes to the destination point, there still be a risk of losing data: the data itself can be damaged or even destroyed completely. But the most amazing thing about the Internet is the efficiency in transmitting data: the data is divided into small pieces called packets; it’s NOT necessary that all packets are routed through the same path, and each packet independently takes the most efficient route possible; upon reaching the target computer, the packets are reassembled together and if it is the case that any packet fails to reach this computer, an acknowledgement is sent from this computer to resend the lost packets again. This makes the Internet practically indestructible!


In general, we can divide all the computers in a global network into two main categories: servers and clients (the latter include personal devices, mobile phones, computers etc.). A server – is a special computer directly connected to the Internet. And web pages – are just files on the Server’s Hard Drive. Usually servers are located at special places called ‘Data Centers’ – huge buildings made to house and maintain servers.


At the same time, your computer at home is NOT a server! Because your computer is connected to the Internet INDIRECTLY: through your Internet Service Provider (ISP) – an organization which provides you access to the Internet. But why is it so? The thing is that all the web infrastructure (like cables, routers, satellites, cellular towers etc.) that connects all of the Data Centers throughout the world is owned by Internet Service Providers. They own and maintain this infrastructure and that’s why you pay them money to get an access to the Internet; and ISPs, on the other hand, support the current infrastructure and build new infrastructure for you and other customers to improve Internet services and quality. In fact, this whole network infrastructure is called the Backbone of the Internet!


Also we should mention the fact that all the computers in the Internet are connected together NOT just like: computer – cable – computer – cable etc. In this case the effectiveness of such network wouldn’t be as high as it is. But routers come into play! A router – is a special networking device that forwards data packets between computer networks. Routers are just like traffic lights or traffic controllers on city crossroads: they forward data packets to the most efficient route possible.


So how does the whole process look like? How computers in this global network communicate with each other? To better understand this we can use a postal network analogy: any postal network with a very good infrastructure uses a special set of BASIC RULES regarding destination addresses (to where we send a letter) and departure addresses (from where we send a letter). Similarly, in the Internet we use protocols. Protocols – are special sets of BASIC RULES for data packet conversion. Each computer has a so-called ‘IP address’: ‘IP’ stands for the ‘Internet Protocol’ address. Just like a postal address, IP-addresses help computers find each other in the global network. But unlike postal addresses, each IP address consists of digits: for example, 192.168.100.101. Protocols set attachment of the source IP address and destination IP address to each packet, rules for routers etc.


Technically, you can access any website just by knowing the server’s IP-address. But it is difficult for a person to remember so many IP-addresses. To solve this problem, DOMAIN NAMES (like youtube.com, google.com) are used to correspond with IP-addresses. Domain names are easier for us to remember (and to use) than the long sequences of numbers of IP-addresses. Domain Name System (DNS) - is like a huge phone-book: if you know a person’s name, you can find the telephone number and call to this person. The DNS provides the same service: you type the name (the domain name like youtube.com) and you get the corresponding IP address, and then you are connected to the server located at this IP address.


You probably already know that satellite Internet has a bad reputation because of high latency (or ping). Latency – is a DELAY in time that it takes for data to travel from your computer to the server and back. And ping – is a method of measuring latency in milliseconds. But what causes latency? First of all, the speed of light: data is transported via optical fiber (cables) or via electromagnetic signals (like from a satellite or from a cellular tower) and travels at the speed of light. According to rough calculations, it takes about 100ms for data to circle the Earth. But the speed of light is NOT the main cause of latency. Latency is mainly caused by processing times at routers: a packet has to be processed by a router after router after router and so on, so number of hops that this packet has to travel to get all the way across the world is quite large, and every time a router has to pick up and make a decision about this packet and pass it on; that seriously adds latency to the Internet connection.


So how to reduce latency? It’s a common misconception that buying more bandwidth will reduce latency. NO! It’s wrong! Because imagine your Internet connection as a big highway: there are lots of cars, but they are moving at the same speed (for example, 100 km/h). So, basically, buying more bandwidth is like increasing the number of lanes on our highway. But in situations where latency plays a crucial role (like in video games) the amount of data to be transported in quite low (only a few bits of some location coordinates, bullet trajectories etc.): it’s like only a few cars are moving on our half-empty highway; so more bandwidth (additional lanes) will do absolutely nothing, because our cars are moving at the same speed of 100 km/h.


In the Internet different packets have different priority: it means that some packets are always processed first, because for different applications the protocols used are different:
(There are tons of Internet protocols out there, but here is a few for example:)
TCP: Transmission Control Protocol, is used for the reliable transmission of data over a network.
HTTP: Hypertext Transfer Protocol, is used for transmitting and displaying hypertext content.
FTP: File Transfer Protocol, is used for file transfer (uploading and downloading) over the Internet.
RTP: Real Time Transport Protocol, is used for live video streaming and VOIP calls.
ICMP: Internet Control Message Protocol, is used to send control messages between routers and computers on the Internet. By the way, a ping is calculated using this protocol.
And there are many-many other protocols…


As you can guess, for example, Internet messenger calls packets or video games packets should always be processed first, because ping in that case really matters.


So are there some real ways to reduce latency? Well, from the point of view of a server, there is a thing called CDN: Content Delivery Network. Content Delivery Network (CDN) – is a geographically distributed network of servers, and a copy of your website is stored at each of the server, so regardless of the geographical location each website visitor is directed to the nearest server possible, drastically reducing the latency. But we should mention that CDN will help only in case if the website is static. And if you play video games or speaking via a messenger, then CDN service can NOT be applied in such case.


And from a non-server point of view (from the point of view of a client) we should know that sometimes routers can be configured to push packets to your system first to reduce latency: for example, in case if your neighbors decided to watch YouTube or to download something heavy from the Internet, your traffic will NOT suffer.


So if you provide services and host your own website, then use a CDN. But if you play video games or use, for example, live video streaming, then just ask your Internet Service Provider for higher quality or lower latency routes (to the destination you use the most). That’s simple!


So if you don’t know – now you know!
Thank you!
