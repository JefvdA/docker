# What is this project?
This repository is a collection of Dockerfiles I've created.

My workflow exists of using docker containers while developing, instead of installing software locally. This meant I often develop in docker containers, and sometimes can't find the docker images for my needs online. Thus, I created this repository.

# How do I search for an image in this repository?
Each image is in it's corresponding directory. For example the `symfony` image is located in: `symfony/Dockerfile`

# Where are the images hosted?
The docker images from this repository are hosted on docker hub. More specific, they're under [my account](https://hub.docker.com/u/jefvda)

# What are the github actions for?
To make life easier, I added github actions that automatically push a new version of the docker image to dockerhub, in case the corresponding Dockerfile is updated.

For example, if a commit get's pushed to `main`, and in this commit the `symfony/Dockerfile` is updated, only that specific github action will get triggered and only the `symfony` image will get pushed.

# Can I contribute?
Ofcourse! The more Dockerfiles in this repository, the less time I, or anyone using this repository, will have to spend on searching a docker image for their needs.

If you find any problems with an existing Dockerfile, create an issue in this github repository about it. If you have a concrete idea about how to fix the problem, create an MR for it aswell!
