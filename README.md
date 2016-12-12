# WeatherSimulator

Weather Simulator for generating weather conditions data for various stations and time across the world

# Running the app

To view the Weather Simulator Application, double click the WorldWeatherSimulatorApp-1.0-SNAPSHOT.jar and wait for the App to launch.

The initial screen will get the weather details for the stations for the current date. To generate  weather report for another date , click on Change Report Date button and enter the date of your choice and then submit.

# Build instructions


This project is build with Apache Maven 3.3.9 and Java version 1.8.0_11


In order to build the application following steps needs to be done.


1. Install Java JDK 1.8.0_11 from http://www.oracle.com/technetwork/java/javase/downloads/index.html


2. After installing java set JAVA_HOME under MY Computer-->Advanced Settings-->  Environment Variable Setting as the JDK installed directory  Eg: C:\Program Files\Java\jdk1.8.0_111


3. Once done check the Java installation by running command echo %JAVA_HOME% . You must get the JDK path printed in the command prompt


4. Download  Apache Maven from  https://maven.apache.org/download.cgi

5. Install maven path giving the path until bin folder in path variable


6. Check maven installation by running command mvn -v in command prompt.


7. Depending upon your network setup, you may require extra configuration. Check out the Guide to Configuring Maven if necessary.

 https://maven.apache.org/guides/mini/guide-configuring-maven.html
 
8.  Download the project from the repository to your local directory
 
9.  Go to the project home directory until WorldWeatherSimulatorApp and run command mvn package to generate the project jar

10. Generated jar will be inside target folder. The application can be launched by double clicking the jar.
 



 
