# cs4032-lab2

Uses Java 7 features.
Relies on java.util.concurrent.Executors for thread pooling.
Exploits a quirk of the java language, wherein non-static enclosed class instances are given an implicit reference to the instance of the enclosing class (hence must be instantiated with such an instance, or from non-static code in such a class).

Building
--------
compile.sh
Requires a java compiler in (javac) in the $PATH, builds class files in the curren directory.

Running
-------
start.sh <port> [threads] [backlog]
