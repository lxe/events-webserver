events-webserver
================

![](http://i.imgur.com/ChzUb.jpg)

### Let's write a event-based webserver.

#### Goals:

 - Simplicity over performance over compliance and portability.
 - Learn how to make your own event-based thingy from "scratch".
 - Understandable by me after I write it.
 - Let's see if simplicity == performance. Or at least let's balance it.

#### Constraints:

 - Let's not worry about portability. Let's make this run on Linux (epoll maybe?) or OSX (kqueue?) I'm not sure yet.
 - Do not overcomplicate. Let's not rely on libuv, libev, libevent etc... They are too magic for me at this point.
 - Do NOT overcomplicate. Simplicity over compilance. We don't need to satisfy everything. Let's pretend we are writing a client as well.
 - Let's not layer this with deps and subdeps. Just kernel interfaces and stdlibs if possible.

#### Materials:

 - http://daniel.haxx.se/docs/poll-vs-select.html
 - https://github.com/springmeyer/libuv-webserver
 - http://www.kegel.com/c10k.html
 - https://github.com/h2o/picohttpparser (parser)
 - http parser library? They are optimized already (picohttpparser, joyent's parser). But maybe they take compliance over performance? Maybe.
 - http://mystry-geek.blogspot.com/2012/07/simple-web-server-using-epoll-and.html
 - http://linux.die.net/man/4/epoll
 - https://github.com/cherokee/webserver/blob/master/cherokee/fdpoll-epoll.c
 - http://www.eecs.berkeley.edu/~sangjin/2012/12/21/epoll-vs-kqueue.html
 - https://github.com/shenfeng/dictionary/tree/master/server
 - 


