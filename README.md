# SRE_Challenge

Requirements
------------
For this project, please think about how you would architect a scalable and secure static web application in AWS or another IaaS provider.
ø Create and deploy a running instance of a web server using a configuration management tool of your choice. The web server should serve one page with the following content.

<html>
<head>
<title>Hello World</title>
</head>
<body>
<h1>Hello World!</h1>
</body>
</html>

ø Secure this application and host such that only appropriate ports are publicly exposed and any http requests are redirected to https. This should be automated using a configuration management tool of your choice and you should feel free to use a self-signed certificate for the web server.
ø Develop and apply automated tests to validate the correctness of the server configuration.
ø Express everything in code.
ø Provide your code in a Git repository named SREChallenge on GitHub.com
ø Be prepared to walk though your code, discuss your thought process, and talk through how you might monitor and scale this application. You should also be able to demo a running instance of the host.
