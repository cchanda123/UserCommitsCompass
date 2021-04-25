# UserCommitsCompass

The current code requires the following Java packages to be added manually to the project.
1. java.net.http
2. java.json (It can be downloaded from http://www.java2s.com/Code/JarDownload/java/java-json.jar.zip)

The java.net.http is required to add the authentication headers and accept format to the request.

The java.json helps in JSON parsing.

The program accepts the following three inputs via scanner:
1. The GitHub User Name of user.
2. The GitHub Password of user in the form of Authentication token.
3. The path on which the CSV file must be generated and stored on the user's machine. Please note that that '\' is written as '\\'. For example, "C:\Users\chetan" must be written as "C:\\Users\\chetan".

Output:
1. CSV file of dates ordered in descending order, while is stores in the location specified by user.
2. Average of the differences in hours, for ex: if the average is 1.87 hours, the program will show 1 hour
