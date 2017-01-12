Docker Nginx Static
===============

> Docker build for serving static content with Nginx

## Building & running the image

    docker build -t project-name .
    docker run -d -v $HOME/www:/www -p 80:80 --name project-name project-name

## Or just auto-build. Requires $HOME/www

    ./init
