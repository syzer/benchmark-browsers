DEMO
====
![picture](https://raw.github.com/syzer/benchmark-browsers/master/docs/benchmark-browsers.png)


[https://benchmark-c9-syzer.c9.io/](link)


WAT
===
Multicore JavaScript test of your browser

Contribute
==========
add issues/requests on github
getting Cpu description:
mac: `sysctl -n machdep.cpu.brand_string`
linux `cat /proc/cpuinfo`
windows `go to start> right click on computer > properties`


Installation
=====

        npm i -g serve
        serve ./performance -p $PORT


Roadmap
=======
[ ] show just a general score
[ ] show score as graph bar
[ ] show single vs multi threaded performance
[ ] recalculate benchmark  after V8/JIT warm up
[ ] as Angular module
[ ] Integrate with JS-Spark as module
