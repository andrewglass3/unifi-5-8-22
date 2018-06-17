# unifi-5-8.22
Unifi 5.8.22

This is my latest build for unifi 5.8.22 Stable Candidate

Ensure you have docker engine and docker-compose installed. To start the controller do:

docker-compose up -d

As long as docker is set to start at boot your controller will autostart.

I have mapped persistent data in the docker-compose.yml to /opt/docker/unifi (Modify this accordingly on your system if you wish) with read/write access.

To access your controller in a browser goto https://localhost:8443

Any issues please let me know.

Thanks

Andrew
~              
   
