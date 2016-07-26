# json-prettifier


Add these lines in /etc/apt/sources.list

deb http://ppa.launchpad.net/samy-badjoudj/json-prettifier/ubuntu trusty main 
deb-src http://ppa.launchpad.net/samy-badjoudj/json-prettifier/ubuntu trusty main 

sudo apt-get update;
sudo apt-get insall json-prettifier;

or download it directly : 

https://launchpad.net/~samy-badjoudj/+archive/ubuntu/json-prettifier/+files/json-prettifier_1.4-0ubuntu1_amd64.deb

usage :
Put json as stdin : 
 cat json_file.json | json-prettifier.c 
 or cat json_file.json | json-prettifier | less -R
