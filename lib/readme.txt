Required runtime libraries
==========================

antlr-runtime-4.5.3.jar
- runtime for ANTLR parser generator
- required for runtime

slf4j-api-1.7.21.jar
- Simple Logging Facade for Java (SLF4J), for logging
- required for runtime

cglib-nodep-3.2.4.jar
- CGLIB bytecode generator
- required for runtime


Optional runtime libraries
==========================

slf4j-log4j12-1.7.21.jar
- SLF4J implementation for Log4j 1.2.17
- runtime, optional (consider using a different log provider)

log4j-1.2.17.jar
- Log4j Library for logging
- runtime, optional (consider using a different log provider)


Compile and Build-time libraries - Not part of the binary distribution and not required for runtime
================================

junit-4.11.jar
- JUnit test framework
- buildtime, not required for runtime

antlr-4.5.3-complete.jar
- ANTLR parser generator, for compile-time generation of parser and tree walker from grammars
- buildtime, not required for runtime

mysql-connector-java-5.1.28-bin.jar
- MySQL JDBC driver, for unit testing of database connectivity
- buildtime, not required for runtime
