# SFTP Server a using Docker Container 

I had a quick requirement to support a short term SFTP server. A quick search in Docker Hub found the perfect solution in [atmoz/sftp](https://hub.docker.com/r/atmoz/sftp)

This container allowed for easy config of SFTP users, passwords, folders and keys. A brief look at the docker-compose.yml shows how this is done along with the script createkeys.sh to create persistent keys.  All taken from the Docker Hub support page for the container.

Source for the [atmoz/sftp](https://hub.docker.com/r/atmoz/sftp) can be found GitHub at [atmoz sftp](https://github.com/atmoz/sftp)


