# netty-all-in-one

This project is created for people who want to build the netty all-in-one jar. Since 4.1.69, netty has not provided all-in-one jar in its release anymore, but there are many legacy projects 
which are not managed by maven still using jar dependencies. These projects, including mine, need to upgrade netty to the newest version because of security vulnerabilities.

The project uses pom file in all folder from version 4.1.68 and is modified to fit for the current version.


## How to Use

Put the pom.xml files into the corresponding folder, and then execute ```mvn -PskipTests package``` in the root of project folder. 
When execution finishes, the netty all-in-one jar will be in the ./all/target folder.

## Alternative

You can download the jar file from release folder directly which is built by myself. (I will not build every release!)