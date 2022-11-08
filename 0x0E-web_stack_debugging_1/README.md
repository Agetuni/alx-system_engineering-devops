# Web stack debugging #1

## *Concepts*
For this project, we expect you to look at these concepts:

* [Network basics]()
* [Web stack debugging](https://github.com/Chacha-A-Chacha/alx-system_engineering-devops/tree/master/0x13-firewall#intro)

## Network basics

Networking is a big part of what made computers so powerful and why the Internet exists. It allows machines to communicate with each other.

* [What is a protocol](https://www.techtarget.com/searchnetworking/definition/protocol)
* [What is an IP address](https://computer.howstuffworks.com/internet/basics/what-is-an-ip-address.htm)
* [What is TCP/IP](https://www.techtarget.com/searchnetworking/definition/TCP-IP)
* [What is an Internet Protocol (IP) port?](https://www.lifewire.com/port-numbers-on-computer-networks-817939)

## Tasks :page_with_curl:

* **0. Nginx likes port 80**
  * [0-nginx_likes_port_80](./0-nginx_likes_port_80): 
  Using your debugging skills, find out what’s keeping your Ubuntu container’s Nginx installation from listening on port 80. Feel free to install whatever tool you need, start and destroy as many containers as you need to debug the issue. Then, write a Bash script with the minimum number of commands to automate your fix.

Requirements:

* Nginx must be running, and listening on port 80 of all the server’s active IPv4 IPs
* Write a Bash script that configures a server to the above requirements
* Usage: `./0-nginx_likes_port_80`

* **1. Make it sweet and short**
  * [1-debugging_made_short](./1-debugging_made_short):
  Using what you did for task #0, make your fix short and sweet.

Requirements:

* Your Bash script must be 5 lines long or less
* There must be a new line at the end of the file
* You must respect usual Bash script requirements
* You cannot use `;`
* You cannot use `&&`
* You cannot use `wget`
* You cannot execute your previous answer file (Do not include the name of the previous script in this one)
* `service`(init) must say that `nginx` is not running ← for real