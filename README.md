# Introduction
This is a proof of concept for creating a custom function for Volt, using Phalcon PHP framework.

# Instructions

Start server: `docker-compose up --build`

Find out the container ip: `docker ps` and `docker inspect <container_name_from_previous_command>`

View in the browser: `http://<ip_found_on_previous_command>`

# About

You should be especially interested in the following files:

* project/app/config/services.php
* project/app/views/index/index.volt

They are responsible for creating and using a new custom Volt function called `baseImagesURL()`,
which can be used analogously as the `url()` function, which is a standard Volt function.
