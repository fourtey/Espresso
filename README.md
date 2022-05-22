Espresso - 1.5.2 
===========

This is my horrific attempt at optimizing and making production ready server software for legacy minecraft versions (1.5.2-1.8.8) 
DO NOT USE THIS FOR YOUR OWN SERVER, IT IS NOWHERE NEAR GOOD OR READY FOR PRODUCTION, THIS IS JUST SOMETHING I DO IN MY FREE TIME

Espresso-1.5 uses the latest stable commit from Spigot's bitbucket repo, prior to updating to 1.6

Compilation
-----------

We use maven to handle our dependencies.

* Install [Maven 3](http://maven.apache.org/download.html)
* You're also gonna need craftbukkit, minecraft_server (mcdev) and bukkit, these are kinda tricky to find so if you're crazy enough to want to tinker with my 1.5 spigot fork, hmu on discord

    * *Note*: I have removed specialsource, or overmapped depending on the version, and as a result this will not work with the legacy bukkit-api methods, only the latest ones