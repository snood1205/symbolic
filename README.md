Symbolic
===================

This project exists to do Symbolic arithmetic. The current goals is to have a Computer Algebra system and basic calculus features. The current estimated completion time for these goals is 3-6 months with the hopes that it will be finished sooner. If you would like to contribute to this project please contact me at [snood1205@gmail.com](mailto:snood1205@gmail.com).

Documentation
-------------

The documentation is hosted on [github](https://snood1205.github.io/symbolic). 
You can view the [Javadoc](https://snood1205.github.io/symbolic/apidocs/), 
[JUnit Test Javadoc](https://snood1205.github.io/symbolic/testapidocs/) and the 
[Maven Project Documentation](http://snood1205.github.io/symbolic/maven/) there.

Where can I get the latest release?
-----------------------------------
You can download source and binaries right here on github.

Requirements
--------------
+ Git
+ Java (JDK 8+)
+ Maven

Installation
-----------------------------------
1. Make sure you've installed all [requirements](#requirements)
2. Clone this repository `git clone https://github.com/snood1205/symbolic.git`
3. Change into the new repository `cd symbolic`
4. Run `mvn package`
5. Run the `.jar` produced by the previous command. The name currently should be `Symbolic-0.1-PREALPHA.jar` and the location `jar` is in `symbolic/target`. You can run this from the command line with the command `java -jar target/Symbolic-0.1` from within the `symbolic` directory.

Contributing
------------

We accept contributions via github. The [developer mailing list](https://groups.google.com/d/forum/symbolic-ml) is the main channel of communication for contributors.
There are some guidelines which will make applying PRs easier for us:
+ No tabs! Please use 2 spaces for indentation.
+ Respect the code style. It is based on [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html).


To actually contribute code:
1. Fork this repo
2. Create a branch with a descriptive name: `git checkout -b feature/new-feature`
3. Comment your code using Javadoc
4. Create comprehensive JUnit Tests (Version 4.12)
5. Comment your JUnit Tets using Javadoc
6. Run `mvn package test clean`
7. Make sure nothing in the previous step failed
8. Commit changes: `git commit -am 'Added [feature name]`
9. Push changes: `git push origin feature/new-feature`
10. Submit a pull request

License
-------
Code is under the [GNU LGPLv3](LICENSE).
