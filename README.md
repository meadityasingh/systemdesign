# systemdesign
This Repository contains concepts of systemdesign
## Content Delivery Network (CDN):

### What is a content delivery network (CDN)? | How do CDNs work?
A content delivery network (CDN) is a geographically distributed group of servers that caches content close to end users. A CDN allows for the quick transfer of assets needed for loading Internet content, including HTML pages, JavaScript files, stylesheets, images, and videos.

A properly configured CDN may also help protect websites against some common malicious attacks, such as <b>Distributed Denial of Service (DDOS) attacks.</b>

A CDN does not host content and can’t replace the need for proper web hosting, it does help cache content at the network edge, which improves website performance.

### The benefits of using a CDN?

1. <b>Improving website load times</b> - By distributing content closer to website visitors by using a nearby CDN server (among other optimizations), visitors experience faster page loading times.
2. <b>Reducing bandwidth costs</b> - Bandwidth consumption costs for website hosting is a primary expense for websites. Through caching and other optimizations, CDNs are able to reduce the amount of data an origin server must provide, thus reducing hosting costs for website owners.
3. <b>Increasing content availability and redundancy</b> - Large amounts of traffic or hardware failures can interrupt normal website function. Thanks to their distributed nature, a CDN can handle more traffic and withstand hardware failure better than many origin servers.

4. <b>Improving website security</b> - A CDN may improve security by providing DDoS mitigation, improvements to security certificates, and other optimizations.

### How does a CDN work?
At its core, a CDN is a network of servers linked together with the goal of delivering content as quickly, cheaply, reliably, and securely as possible. In order to improve speed and connectivity, a CDN will place servers at the exchange points between different networks.

These <b>Internet exchange points (IXPs)</b> are the primary locations where different Internet providers connect in order to provide each other access to traffic originating on their different networks. By having a connection to these high speed and highly interconnected locations, a CDN provider is able to reduce costs and transit times in high speed data delivery.

![internet exhange point](/images/ixp.png)

Beyond placement of servers in IXPs, a CDN makes a number of optimizations on standard client/server data transfers

