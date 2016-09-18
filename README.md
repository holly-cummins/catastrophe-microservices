# Cat-astrophe Microservices Sample


# About this sample

This sample is an application composed of  microservices. If you’re wondering about the names – all good internet content involves cats. This sample was written
to be used as a live demo, and I have some experience of live demos, so I called it – of course – cat-astrophe. 

The following projects comprise this application: 

* [A web front end, catastrophe-web](http://github.com/holly-cummins/catastrophe-web)
* [A persistent store of user information, catastrophe-users](http://github.com/holly-cummins/catastrophe-users)
* [A cat scoring service, catastrophe-scoring](http://github.com/holly-cummins/catastrophe-scoring)
* [A cat repository, catastrophe-cats](http://github.com/holly-cummins/catastrophe-cats)

Service discovery is handled by [a Liberty extension which automatically registers services](https://github.com/WASdev/sample.consulservicediscovery) with [a Consul service registry](https://www.consul.io). 

![catastrophearchitecture.png](High-level application architecture) 

This application is designed to run on a [raspberry pi](http://www.linksprite.com/linksprite-pcduino/) (and optionally [Bluemix](http://bluemix.net)), and runs on [WebSphere Liberty](http://wasdev.net). 

**[License information](LICENSE.txt)** 

## Getting started 

Cloning this project should clone each constituent microservice. Each one has a gradle build and a deploy to bluemix button on the the README. 

# Dependencies 

This sample uses [WebSphere Liberty](http://wasdev.net), Java EE interfaces, the [webjars](http://www.webjars.org) bundles of the [Bootstrap UI framework](http://getbootstrap.com), and the [Liberty Consul Service Discovery sample](https://github.com/WASdev/sample.consulservicediscovery).

# More information 

* [A Blog post about microservices and this sample](https://developer.ibm.com/wasdev/blog/2016/06/01/putting-micro-microservices/)
* [The talk which accompanies this demo](http://www.slideshare.net/HollyCummins/microservices-from-dream-to-reality-in-an-hour")
* [Liberty and microservices](https://developer.ibm.com/wasdev/docs/microservices/)

