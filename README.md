DEMO
====
[https://benchmark-c9-syzer.c9.io/](link)


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



TODO
====

[ ] as Angular module

[ ] Integrate with JS-Spark as module

Roadmap
=======
[ ] show just a general score
[ ] show score as graph bar
[ ] show single vs multi threaded performance
[ ] recalculate benchmark  after V8/JIT warm up
