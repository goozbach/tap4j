# tap4j

tap4j - Simple implementation of the 
[Test Anything Protocol](http://www.testanything.org) (TAP) for Java.

    1..2
    not ok 1 - Something went wrong
      ---
      timestamp: 2012-12-10-20:31:01:021sss
      extensions: 
        files: 
          apache.err.log:
            File-Type: text/plain
            File-Content: <Base64-Encoded>
            File-Size: 685
            File-Name: apache.err.log
      ...
    ok 2 # SKIP skipping due to previous errors

TAP is a test protocol that can be used to report test execution. It has been 
created with Perl 1, around 1988, and is the main format in Perl. A test 
harness executes tests and generates TAP, in the same way that a test harness 
can execute tests and generate other formats such as TestNG, JUnit or SubUnit.

SubUnit and TAP can be extended. Different than TestNG and JUnit, although 
there is a specification for the protocol, using YAML(ish) you can include 
extra information about your tests, such as attachments.

## Projects using tap4j

* Jenkins TAP Plug-in

* Jenkins TestLink Plug-in

* JinFeng

## Build status

[![Build Status](https://buildhive.cloudbees.com/job/tupilabs/job/tap4j/badge/icon)](https://buildhive.cloudbees.com/job/tupilabs/job/tap4j/)

## Authors and licensing

See AUTHORS or pom.xml for information regarding the authors and LICENSE 
or pom.xml for Licensing.
