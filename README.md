# berember
Java program for remembering Security+ Terms

# Directory Contents
`mvnw` Executable Linux script that can be used in place of a fully-installed maven executable<br />
`mvnw.cmd` Executable Windows (batch) script version of the above<br />
`/mvn` Hidden folder that holds the maven wrapper java library and its properties file <br />

`/src` Java source files
`/target` Build at run time, temporary class files

# Clean

## Using mvnw (if you do not want to or do not have install maven)
`./mvnw clean install` (linux)<br/>
`mvnw.cmd clean install` (windows)<br/>
Note that if you do not have the specified maven version in the mvnw properties, it will be downloaded and placed in the folder `$USER_HOME/.m2/wrapper/dists` of your system.


## Using traditional maven (if you do have maven)
`mvn clean install`<br/>

