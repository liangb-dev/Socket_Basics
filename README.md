
# Socket Basics

This project is a simple client program that communicates with the server on login-faculty.ccs.neu.edu and listens to requests on TCP port 3700. There are six types of messages:
  - HELLO\n
  - IAM 0123456\n
  - INFO 123456\n
  - REPLY 123456\n
  - NULL 000000\n
  - KEY 1234567\n
  
The purpose of the Client program is to give the correct response back to the server, and eventually after multiple exchanged messages the server will return a secret flag back to the user. 
