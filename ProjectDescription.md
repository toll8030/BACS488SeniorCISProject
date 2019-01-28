# BACS488SeniorCISProject
>>> A Tiny Web Server

### Project Description  
1. Overview of the Tiny Web Server (TW) </br>
  A Web server is a program that uses HTTP (Hypertext Transfer Protocol) to serve the files 
  that form Web pages to users, in response to their requests, which are sent to the server by 
  their computers’ HTTP clients (browsers). This document contains the requirements for a miniature 
  Web server called “Tiny Web Server” (TW). TW only responds to HTTP GET messages and only serves 
  static HTML pages and images. It has a desktop interface showing each connection separately. 

##### 2. Definitions  </br>
  Server – The TW server running on a computer  
  Client – The browser on the user’s computer. 
  Request – HTTP GET request. The server responds to other HTTP requests with an HTTP 400 Bad Request. 
  Response – The HTTP response sent back from the server to the client in response to its HTTP request. 
  Connection – TCP connection made between the client and the server initiated by the client. 
  Serve – Responding to a request. 

##### 3. User Requirements  </br>
  The server must allow the user to choose the path where the web pages and files are stored. 
  The server must show all requests and responses from and to each browser in separate pages. 
  The server must accept HTTP/1.1 persistent connections. 
  The server must serve GET requests as defined in RFC 7231 by implementing responses 200, 400, and 404. 
  The responses should include the HTTP fields required for the browser to legibly show a static html page and its corresponding images. 

##### 4. Project-Specific Requirements  </br>
  The serve must be able to handle multiple simultaneous connections. 
  Each connection to the server must be handled by exactly one thread. 
  The server must have a GUI. 
  
##### 5. Deliverables  </br>
  A complete requirements document including system architecture, system requirements, syntax and semantics of messages, server data model, etc. and appendices as appropriate. 
  Design documents detailing all system models required by the course. 
  Fully-functioning implementation of the server. 
  Source code of the server. 
  A short video demonstrating the main functions of the system. 
  Test documents as required by the course. 

##### 6. Platforms  </br>
  The server application can be implemented on any desktop platform.
