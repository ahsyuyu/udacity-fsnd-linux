# Item catelog - Udacity
### Full Stack Web Development ND
_______________________
## About
This project deploys the catalog application to a linux server which is secured and also hosts as our database server

- IP address: http://54.202.75.10
- URL: http://54.202.75.10.xip.io/

## Software installed
- apache2
- python3
- libapache2-mod-wsgi-py3
- postgresql
- git

## Configuration made
- In `/etc/ssh/sshd_config`
    -  Change the default port for ssh is changed from `22` to `2200`
    -  Set `PermitRootLogin` and `PasswordAuthentication`to `no`to disable root login and password based login through ssh
