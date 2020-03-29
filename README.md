# WordCountProject

WordCount is a simple java application to  count max repeated words in a file.

# Installation

A fully working sample Maven project.

To build it, you will need to download and unpack the latest (or recent) version of Maven (https://maven.apache.org/download.cgi)
and put the `mvn` command on your path.
Then, you will need to install a Java 1.8 (or higher) JDK (not JRE!), and make sure you can run `java` from the command line.
Now you can run `mvn clean install` and Maven will compile your project, 
an put the results it in a jar file in the `target` directory.

#  Testing

MaxRepeatedWord.java file has main method where few test case are written to test in console.
you add more test cases for understanding.

MaxRepeatedWordTest.java contains junit test cases which are automatically executed when we build the application.

The sample.txt file present in the class path contains paragraph which will be read by java class. Add more words as your desire to sample.txt to do custom testing 

# A couple of Maven commands

Once you have configured your project in your IDE you can build it from there. However if you prefer you can use maven from the command line. In that case you could be interested in this short list of commands:

* `mvn compile`: it will just compile the code of your application and tell you if there are errors
* `mvn test`: it will compile the code of your application and your tests. It will then run your tests (if you wrote any) and let you know if some fails
* `mvn install`: it will do everything `mvn test` does and then if everything looks fine it will install the library or the application into your local maven repository (typically under <USER FOLDER>/.m2). 
