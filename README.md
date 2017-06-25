# Deploying To Linux Server Project

## Intro 
> This project is part of udacity's full-stack nanodegree project. In this project I have used amazon's lightsail services to host a virtual private server and deployed a flask website.

##
> Live version is on http://13.126.197.75/

## Summary of what I did in this project.
1. Used Amazon's LightSail Service to host a virtual private server
2. Created a new user 'grader' and granted sudo permission to the 'grader' user.
3. Generated public and private keys for authentication using ssh-keygen on my local machine
4. Added public key on server by adding private key to 'grader's ~/.ssh/authorized_keys
5. Disable remote login. Only key-based authentication is allowed
6. Blocked all ports and only allowed http port 80, ntp port 123 and ssh port 2200
7. Using non-default port for ssh ie. from port 22 to port 2200
8. Configured local timezone
9. Configure Apache to serve WSGI application
10. Install and configure postgresql
11. Created database user named catalog and database named catalog
12. Installed git
13. Cloned the catalog project
14. Configured apache to host the above app
15. Update OAuth information for Google+ Login

## To Access Server
> Use IP Address = 13.126.197.75 and PORT = 2200
> Use the provided private key for key-based authentication
