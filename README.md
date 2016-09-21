# log4j2 Omnifaces Webapp

Build WAR file and deploy in Tomcat or run directly from Eclipse WTP.

`ERROR StatusLogger No log4j2 configuration file found. Using default configuration: logging only errors to the console.`

Comment out Omnifaces dependency to see the difference (log4j2 will actually look at the place specified in the context parameter). Depending on the Tomcat configuration you will either see no error and normal logging output or an error message including the path which was tried to be accessed.

`ERROR StatusLogger Unable to access file://C/app/eclipse/conf/custom_log4j2.xml`
