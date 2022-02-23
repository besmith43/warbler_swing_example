# warbler_swing_example
this is example code to show various ways that a jruby project that utilitizes Java's Swing gui can be compiled


## example 1
This jar file is built by taking the source example.rb file and running it through jrubyc to produce a .class file.  Then this file is combined with the manifest and jruby.jar files into a jar file.  It can be run with the following command: java -jar example1.jar

## example 2
This jar file is built by taking the jruby.jar file and overloading it's jar-bootstrap.rb with a custom one.  This can be run with the same command as the first example.

## example 3
This jar file is built by warbler.  It's a build tool to produce jar or war archives for command line or graphical applications and web applications respectively.  So far this successfully builds the jar, but the interface only appears for a moment before disappearing and the application closes out.
