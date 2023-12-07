# cozy-stack docker compose

## About Cozy and cozy-stack

![Cozy Logo](https://cdn.rawgit.com/cozy/cozy-guidelines/master/templates/cozy_logo_small.svg)

[Cozy](https://cozy.io) is a platform that brings all your web services in the
same private space. With it, your web apps and your devices can share data
easily, providing you with a new experience. You can install Cozy on your own
hardware where no one profiles you.

Cozy-stack is the core server of the Cozy platform. It consists of a single
process, *the Cozy stack*.

[Full Cozy-Stack documentation here](https://docs.cozy.io/en/cozy-stack/).

## What is this cozy-stack docker compose?

Cozy-stack docker compose is a docker compose configuration that will let you
start a full-featured all-in-one selfhosted cozy-stack in a docker environment
with its CouchDB database and a Caddy reverse-proxy with on-demand TLS.

It's goal is to help deploying self-hosted environments on whatever OS provded
that you have a working docker engine with docker-compose.

## Running a cozy-stack environment using docker compose

You can refer to our [Self Hosting with docker documentation](https://docs.cozy.io/en/tutorials/selfhosting/docker/) for usage details about this repository.
