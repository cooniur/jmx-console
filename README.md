JMX Console
===========

This is simple JMX MBean viewer that comes in the form of a JARred web fragment.  Building this project results
in a JAR file, simply dropping that JAR file into your WEB-INF/lib directory will expose the JMX beans at the
url /jmx-console.

Bugs
----

There's one weird bug I haven't been able to figure out: although the JSPs in META-INF/resources/jmx-console are visible
through the web browser, the master.css file always returns a 404.  If you figure this out, please fork the project
and issue a pull request.  I'd appreciate it!

Notes
-----

I don't make any representation that this is actually very good code.  It's written with bare servlets and everything is
pretty cobbled together - but who cares, since it's just a utility to add to an existing web app.