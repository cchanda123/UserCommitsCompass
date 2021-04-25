# UserCommitsCompass

The current code requires the following Java packages to be added manually to the project.
	1. java.net.http
	2. java.json (It can be downloaded from http://www.java2s.com/Code/JarDownload/java/java-json.jar.zip)

The java.net.http is required to add the authentication headers and accept format to the request.

The java.json helps in JSON parsing.

The program accepts 3 inputs
1. User Name(Git)
2. Password (Put in the Authentication token)
3. CSV file storage location

Output:
--> CSV file of dates ordered in descending order, while is stores in the location specified by user.
--> Average of the differences in hours, for ex: if the average is 1.87 hours, the program will show 1 hour
