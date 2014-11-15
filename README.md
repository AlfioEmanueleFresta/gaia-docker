# `gaia-docker`

This Repository contains various Docker images related to [Italian Red Cross' Gaia Project](https://github.com/CroceRossaCatania/gaia).

## `gaia-req` 

* Latest version is: `alfioemanuele/gaia-req:v2`;
* Exposes ports: `80`;
* Built on `ubuntu:14.04`.

This is a simple Ubuntu 14.04 image with PHP 5.5.9, Apache2, and other PHP extensions needed in a Gaia application server.

## `gaia-dev`

* Latest version is: **COMING SOON**;
* Exposes ports: `80`;
* Built on `gaia-req`.

This is an all-in-one image containing a full development environment (Gaia, Apache2, PHP, MongoDB, MySQL 5.6, Redis, GIT, ...).
