# Setting FileRun Using Docker

* Help Sought from [here](https://hub.docker.com/r/afian/filerun/) and [here](http://docs.filerun.com/docker)

* Pre-Requisites
    * Docker Installed and nothing else.

* Clone this Repository and Go to this Folder FileRun
    * Windows
        * Just Run this command
            * docker-compose up -d
        * In case You want to change the Drive Location where you want to keep the files,
            * See the last two lines of yml files, change them (left hand side ones). (No need to create the folders, just change the drive.)
    
    * Linux-Based Machine
        * See the last two lines of yml files, change them with something like below, unless you want to keep them at some custom location.
            * /FileRun/html:/var/www/html
            * /FileRun/user-files:/user-files