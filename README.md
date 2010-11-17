# Casserole

Casserole is a GUI tool for managing and monitoring Cassandra clusters.  It is
written in Java and forms generated by JFormDesigner (not needed to run).

## Building

compile with `ant build`

build everything with `ant dist`

## Running

There are several ways you can run Casserole:
1. `ant build dist` and double-click on `dist/cassandra-casserole.jar'.
2. `ant run`
3. Use webstart by clicking on a [jnlp](http://www.dusbabek.org/~garyd/casserole/casserole.jnlp) I've uploaded to my website.
   Nothing is signed, so you'll get security warnings every time Casserole tries to create a connection to a node.
4. If you're a masochist, the main class is `org.apache.cassandra.casserole.Main`.

