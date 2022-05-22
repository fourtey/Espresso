Espresso
===========

This is my horrific attempt at optimizing and making production ready server software for legacy minecraft versions (1.5.2-1.8.8) 
DO NOT USE THIS FOR YOUR OWN SERVER, IT IS NOWHERE NEAR GOOD OR READY FOR PRODUCTION, THIS IS JUST SOMETHING I DO IN MY FREE TIME

Compilation
-----------

We use maven to handle our dependencies.

* Install [Maven 3](http://maven.apache.org/download.html)
* Check out and install [Bukkit](http://github.com/Bukkit/Bukkit)
    * *Note*: this is not needed as the repository we use has Bukkit too, but you might have a newer one (with your own changes :D)
* Check out this repo and: `mvn clean package`

    * *Note*:I have removed specialsource, or overmapped depending on the version, and as a result this will not work with the legacy bukkit-api methods, only the latest ones