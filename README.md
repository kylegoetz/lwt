# LWT Docker Fork

This repository hosts the LWT codebase created by some person whose name I cannot find, but the project is
published at http://lwt.sourceforge.net/.

What sets this repo apart from the original one is that I've deleted the sample config files, configured a Docker Compose script
to launch an nginx container hosting the LWT source and linking to a mariadb container to store the data.

## To launch LWT in a Docker container

1. Copy the contents of `docker-compose.yml` into a file on your computer.
2. From the same directory, run `docker-compose up`.
3. Go to `http://localhost:8080` in your browser.
