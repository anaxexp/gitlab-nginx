# Nginx for Gitlab Docker Container Image 

[![Build Status](https://travis-ci.org/anaxexp/gitlab-nginx.svg?branch=master)](https://travis-ci.org/anaxexp/gitlab-nginx)
[![Docker Pulls](https://img.shields.io/docker/pulls/anaxexp/gitlab-nginx.svg)](https://hub.docker.com/r/anaxexp/gitlab-nginx)
[![Docker Stars](https://img.shields.io/docker/stars/anaxexp/gitlab-nginx.svg)](https://hub.docker.com/r/anaxexp/gitlab-nginx)
[![Docker Layers](https://images.microbadger.com/badges/image/anaxexp/gitlab-nginx.svg)](https://microbadger.com/images/anaxexp/gitlab-nginx)

## Docker Images

!!! For better reliability we release images with stability tags (`anaxexp/gitlab-nginx:10-1.13-X.X.X`) which correspond to [git tags](https://github.com/anaxexp/gitlab-nginx/releases). We **STRONGLY RECOMMEND** using images only with stability tags. 

Overview:

* All images are based on Alpine Linux
* Base image: [anaxexp/nginx](https://github.com/anaxexp/nginx)
* [Travis CI builds](https://travis-ci.org/anaxexp/gitlab-nginx) 
* [Docker Hub](https://hub.docker.com/r/anaxexp/gitlab-nginx)

Supported tags and respective `Dockerfile` links:

* `10-1.13`, `latest` [_(Dockerfile)_](https://github.com/anaxexp/gitlab-nginx/tree/master/Dockerfile)

## Environment Variables

| Variable               | Default Value       | Description |
| ---------------------- | ------------------- | ----------- |
| `NGINX_WORKHORSE_HOST` | `workhorse:8181`    |             |
| `NGINX_SERVER_NAME`    | `default`           |             |
| `GITLAB_PAGES_DOMAIN`  |                     |             |
| `GITLAB_PAGES_URL`     |                     |             |
| `GITLAB_HTTPS`         |                     |             |

See [anaxexp/nginx](https://github.com/anaxexp/nginx) for all variables.

## Orchestration actions

See [anaxexp/nginx](https://github.com/anaxexp/nginx) for all actions.

## Deployment

Deploy GitLab to your own server via [![AnaxExp](https://www.google.com/s2/favicons?domain=anaxexp.com) AnaxExp](https://anaxexp.com).
