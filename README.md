events-webserver
================

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
 - http parser library? They are optimized already (picohttpparser, joyent's parser). But maybe they take compliance over performance? Maybe.


