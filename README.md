eeAdNetwork
===========

eeAdNetwork (Energy-Efficient Ad Network) is an extension to the existing funcionality of 
AdMob advertising network. Its main goal is to fetch advertisement in an energy efficient way. 
It consists of the following applications:

1) https://github.com/iprockova/ProxyServer

ProxyServer is an Android applications that intercepts all the advertisement requests and 
provides an advertisement reply from a local cache. Only the first time the advertisements
are relayed, and after that they are replayed from the cache.

2) https://github.com/iprockova/RelayServer

RelayServer is an Java-based server application that receives advertisement requests and relays them to 
the AdMob servers. The advertisement replies are sent to the mobile application from the RelayServer.
