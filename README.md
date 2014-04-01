# Redlink Java SDK 

## Unit Tests

To properly run the test suite there are few requisites need to be in place:

* At my.redlink.io, register an analysis chain with the name 'test' and a dataset with the name 'test'
* Create an application, and copy the api key into the src/test/resources/api.key file
* Run the test with Maven or any compatible IDE

Test are skipped by default, so then you need to explictly enable them:

    mvn test -DskipTests=false

## About

This SDK SDK is avaiable under the business-friendly license [Apache License, Version 2.0][ASL2]. 
Therefore, you are completelly free to use the software for any purpose, to distribute it, 
to modify it, and to distribute modified versions of the software, including closed-source, 
under the terms of the license, without concern for royalties.

Further details at [dev.redlink.io][dev].

[dev]: http://dev.redlink.io/sdk
[ASL2]: http://www.apache.org/licenses/LICENSE-2.0.html
