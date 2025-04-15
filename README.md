Description:
UNIXTime2Human is a minimalist web application that converts UNIX timestamps into a human-readable format directly from the browser. The project is designed as a simple wrapper around the classic date utility — a straightforward idea that demonstrates how quickly you can turn system functionality into a web interface.

go.mod  
go.sum  
main.go  
views/index.html


Objective:
To demonstrate how simple it is to link a browser with the power of command-line tools. Instead of reinventing the wheel, the goal is to wrap the power of UNIX in a few lines of Go code. The result is a fast, intuitive, and functional tool — exactly what a pet project should be.

Final:
While exploring the execution environment and project structure, I discovered the flag within the environment variables:
HOSTNAME=e7c1352e71ec  
PWD=/home/challenge  
HOME=/home/challenge  
GOLANG_VERSION=1.15.7  
FLAG=flag{7da6c7debd40bd611560c13d8149b647}  
SHLVL=0  
PATH=/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin  
_=/usr/bin/env
