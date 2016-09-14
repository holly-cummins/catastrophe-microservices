# Cat-astrophe Microservices Sample
# cats Service


# About this sample

This sample is one microservice in a [larger sample 
microservices application](http://github.com/holly-cummins/catastrophe-microservices). If you’re wondering about the names – all good internet content involves cats. This sample was written
to be used as a live demo, and I have some experience of live demos, so I called it – of course – cat-astrophe. 

This service stores information about cats. 

This application is designed to run on a [raspberry pi](http://www.linksprite.com/linksprite-pcduino/) (and optionally [Bluemix](http://bluemix.net)), and runs on [WebSphere Liberty](http://wasdev.net). 

**[License information](LICENSE.txt)** 

## Getting started 

### Eclipse integration 

To set up Eclipse projects, run 

    gradle clean
    gradle eclipse

### Running the server locally (from the command line) 

Run

    gradle runServer

The application should be available on http://localhost:9080.

### Deploying to a single board computer 

To create a zip with the application and all dependencies (including the server), run 

    gradle packageServer


### Deploying to Bluemix 

To create a war, run `gradle` from the catastrophe-cats folder.

This can then be pushed to Bluemix with 

    cf push -p build/libs/catastrophe-cats.war

# Dependencies 

This sample uses [WebSphere Liberty](http://wasdev.net), Java EE interfaces, the [webjars](http://www.webjars.org) bundles of the [Bootstrap UI framework](http://getbootstrap.com), and the [Liberty Consul Service Discovery sample](https://github.com/WASdev/sample.consulservicediscovery).

# More information 

* [A Blog post about microservices and this sample](https://developer.ibm.com/wasdev/blog/2016/06/01/putting-micro-microservices/)
* [The talk which accompanies this demo](http://www.slideshare.net/HollyCummins/microservices-from-dream-to-reality-in-an-hour")
* [Liberty and microservices](https://developer.ibm.com/wasdev/docs/microservices/)

