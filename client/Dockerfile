# make an container with nginx:alpine as base
FROM nginx:alpine

# Workdir is nginx webfolder
WORKDIR /usr/share/nginx/html

# copy all needed:
COPY . .



    # build:
    #   context: ./docker/
    #   dockerfile: nginx-with-openssl.Dockerfile
    # image: "nginx-with-openssl"
    # volumes:
    #   - ./client:/usr/share/nginx/html
    #   - ./docker/nginx/default.conf:/etc/nginx/conf.d/default.conf
    #   - ./docker/certs:/etc/ssl/certs
    #   - ./docker/openssl:/mnt/openssl
    # ports:
    #   - "8080:80"
    #   - "443:443"
    # env_file: ./docker/fqdn.env
    # entrypoint: /mnt/openssl/create.sh
    # command: ["nginx", "-g", "daemon off;"]