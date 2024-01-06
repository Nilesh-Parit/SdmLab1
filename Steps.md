-------------------------------SDM-------------------------------------

1) make a folder + open cmd first command -> "npm init"(package.json is created)
- make public folder --> images folder(put your images)
3) open this folder in vs code 
- npm install express
4) make server.js outside public folder
- check by running node server.js
- test it in your browser
5) make docker file 
      write FROM node:18
	    WORKDIR /app
	    COPY package.json /app
	    RUN npm install
	    COPY . /app
	    CMD node server.js 

6) Now upload this project on github
         i) make new repositary (gitignore--node)
         ii) clone it in your system
         iii) if error oocurs clear proxy and set credential 
              "8 Commands"
         iv) copy our project folder and paste it in repositary cloned folder
         v)  push it on github
7) go on aws login with your credentials
8) lauch instance 
       i) write instance name
       ii) select os as ubuntu
       iii) create key value pair select .ppk file
       iv) launch instance.
9) security --> security group --> edit inbound rules --> add rule --> type=all traffic --> source=anywhere ipv4--> save rule 
10) select particular instance and connect
11) sudo apt update 
12) make folder mkdir folder_name --> go into particular folder --> git clone our project
13) ls --->  go inside our project
14) sudo apt install docker.io
15) sudo systemctl --type=service --state=running
16) sudo docker build -t image_name(lowercase) .
17) to check image --> sudo docker images
18) sudo docker run -d -p port_number:port_number image_name
19) copy ip address
20) go into the browser type copiedIpAdddress:port_number
21) done!!!!!!
