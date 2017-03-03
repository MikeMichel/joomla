This is a  docker-compose file for joomla dev versions (not ready for production!). Parts of this repo are taken from the official joomla docker repo.

## How-to run

You need to install [docker-compose](https://docs.docker.com/compose/install/) then clone this repository or take just the docker-compose file. In the file you may change the logins and passwords then fire it up with `docker-compose up`

You should be able then to access the joomla installation at http://localhost:8080 . In the database configuration dialog choose `mysql` as the `Host Name` and insert username, password and database name like it is configured in the docker-compose file.

## Host it at sloppy.io

https://sloppy.io is a docker hosting platform. You get free *.sloppy.zone domains and free lets encrypt ssl certificates for your own domains.

Here is a video how to setup up joomla at sloppy.io https://vimeo.com/206595268

