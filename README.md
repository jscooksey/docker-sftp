# SFTP Server a using Docker Container 

^2022-03-19^

I had a quick requirement to support a short term SFTP server and q quick search in Docker Hub found [atmoz/sftp](https://hub.docker.com/r/atmoz/sftp)

This container allowed for easy config of SFTP user/folders and keys.

Source for rthe same can be found at [GitHub atmoz sftp](https://github.com/atmoz/sftp)

Base config can be found by checking out the dcoker-compose.yml file which maps paths, as user.conf file as well as persistent keys.
