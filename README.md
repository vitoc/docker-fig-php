docker-fig-php
==============

Very simple boilerplate to setup a PHP web development environment with Docker and Fig.

Requirements
============

1. Docker
2. Fig

How To Use
==========

To start (assuming PHP sources for web application within src directory):

    # fig up

While container is running, code changes in src/ will take effect within the container.

To stop: 

    # fig stop

Other possibilities:

    # fig --help