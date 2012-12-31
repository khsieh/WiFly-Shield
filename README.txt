This library is based on the Arduino 1.0-compatible library here:
https://github.com/jmr13031/WiFly-Shield

Ron Guest's modification allowed join() to work with SSIDs with spaces if the spaces were replaced with '$':
http://ronguest.com/blog/2011/05/wifly-twists-turns-but-it-works/

I've modified Ron's code to allow SSIDs with spaces to be passed to join() and integrated it with the Arduino 1.0-compatible library.

Enjoy!
Kane Hsieh
www.kanehsieh.com
kane@post.harvard.edu

--

This is a library for the Arduino-compatible WiFly Shield available from
SparkFun Electronics:

  <http://sparkfun.com/products/9954> 

The library also provides a high-level interface for the "SC16IS750
I2C/SPI-to-UART IC" used in the WiFly shield but also available on a
separate breakout board:

   <http://www.sparkfun.com/products/9981>

See the file 'src/WiFly/README.txt' for more detail.
