# UserCommitsCompass

The current code requires the following Java packages to be added manually to the project.
	1. java.net.http
	2. java.json

The java.net.http is required to add the authentication headers and accept format to the request.

The java.json helps in JSON parsing.

The program accepts 3 inputs
--> User Name(Git)
--> Password (Put in the Authentication token)
--> CSV file storage location

Output:
--> CSV file of dates ordered in descending order, while is stores in the location specified by user.
--> Average of the differences in hours, for ex: if the average is 1.87 hours, the program will show 1 hour
