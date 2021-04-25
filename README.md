# UserCommitsCompass

Introduction

The given code performs the following operations:
Part # 1 - Accepting user input and generating a CSV file with the time stamps of the first 60 commits.
Part # 2 - Calculating the mean of the time difference in hours between two adjacent commits.

Setup

The current code requires the following Java packages to be added manually to the project.
1. java.net.http
2. java.json (It can be downloaded from http://www.java2s.com/Code/JarDownload/java/java-json.jar.zip)

The java.net.http is required to add the authentication headers and accept format to the request.

The java.json helps in JSON parsing.

Required Input

The program accepts the following three inputs via scanner:
1. The GitHub User Name of user.
2. The GitHub Password of user in the form of Authentication token.
3. The path on which the CSV file must be generated and stored on the user's machine. Please note that that '\' is written as '\\'. For example, "C:\Users\chetan" must be written as "C:\\Users\\chetan".

Expected Output

1. CSV file of dates ordered in descending order, while is stores in the location specified by user.
2. Average of the differences in hours. 

Limitations

1. The mean difference in hours is rounded down to the nearest integer. For example, if the mean difference is 1.87 hours, the program output will display it as 1 hour.