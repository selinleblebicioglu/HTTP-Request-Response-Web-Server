# HTTP-Request-Response-Web-Server
A very simple HTTP request/response web server project written in C.

It's my first time trying system programming in C, so feel free to point out mistakes on my code. 

## How to use

**To compile the code:**
```
gcc server.c -o server
./server -portnum- (as pointed in usage)
```
  
**Then open your web browser:**
```
localhost:-portnum-/-some file name .filetype (must be existed)-
```
  
**Or you can simply just use telnet:**
```
telnet localhost -portnum-
```
  
Note that this code only responses to `GET` request, so you have to use `GET` request for a response.
  
```
GET -existed file name .filetype- HTTP/1.1 \r\n
```
