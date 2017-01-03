# Appleseed/core-stack on Docker Windows
This is a Docker containerized stack for the Appleseed Core Framework on Docker using Windows

##Quickstart:##

Configure and Install docker and docker-compose on your machine or server. Please note that by default this stack installs to port 80 of your site. This may be configured in either the compose file or docker run command to bring up internally. If brought up internally, firewall settings will have to be adjusted to the internal port assigned.

If you are using Windows 2016 Server, the OS now has Docker built-in (but you may have to install compose).
- [Get Docker ](https://www.docker.com/products/overview)
- [Windows Container Docs ](https://aka.ms/WindowsContainers)

### Windows Docker Appleseed Core-Stack Composure
- `md c:\Appleseed`
- `git clone https://github.com/Appleseed/portal-stack.git`
- `git clone https://github.com/Appleseed/search-stack.git`
- `git clone https://github.com/Appleseed/core-stack.git`
- `cd .\core-stack\docker\windows\`
- `docker-compose -p core-stack up -d`
- `docker ps - a`



