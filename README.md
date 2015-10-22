# ln(js)
The natural log appender!

This extremely lightweight JavaScript logging library was written mostly for fun, but also for serving the purpose of providing a logger which doesn't break a script if the console object doesn't exist for some reason!

Initialise a logger with

    var logger = new Logger(); // Logger('warn') would return one with a level of WARN

Set log level with a string representation

    logger.setLevel('info');

Get the value of Euler's constant
    logger.e


Enjoy!
