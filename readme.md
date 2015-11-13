# weave-nginx

To build a Docker image for your site, you'll need to create a `Dockerfile`. For example, if your site is in a directory called `website/`, you could create this `Dockerfile`:

    FROM elarasu/weave-nginx
    COPY website/ /var/www
    CMD 'nginx'

# nginx.conf

The nginx.conf and mime.types are pulled with slight modifications from
the h5bp Nginx HTTP server boilerplate configs project at
https://github.com/h5bp/server-configs-nginx
