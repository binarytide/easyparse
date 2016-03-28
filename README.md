# easyparse
A simple docker sandbox for getting started with Parse Server 

Get up and running with Parse Server(https://github.com/ParsePlatform/parse-server) right out of the box.

Requires Docker(http://docs.docker.com/mac/started/)

Getting started:
<ol>
<li>start up Kitematic</li>
<li>open a terminal and clone this repo</li>
<li>run <code>eval "$(docker-machine env default)"</code> to hook command line into docker (or use quick start terminal(part of Kitematic)</li>
<li>from the cloned folder <code>docker-compose up -d </code>
<li>this will create everything you need to get started. Server will be at your DockerIp:1337 (DockerIp:1337/test provides a simple test to make sure the setup works)
<li>the dashboard can be found at DockerIp:4040 username and passwords can be found in /dashboard/config.json (the default is set to u:user1 p:pass)
</ol>

This is not meant for production, this is merely designed to give you an idea of what it would be like to work with the Parse Opend Source Platform. 
