# {projet}

Add the following lines to yous profile:

    if [ `uname -p` = "arm" ]; then export MS_DEV_CONTAINER_FLAVOR="-bullseye" ;fi

This will allow the devcontainer to use the arm version of the docker image.
