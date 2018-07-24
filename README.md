# Digits docker

## Description

Project was created to use Docker and have possiblity to modify `caffe` at the same time. `Dockerfile` is an exact copy of a Dockerfile available at this [link](https://gitlab.com/nvidia/digits/blob/master/6.0/Dockerfile) with provided few modifications.

## Prerequisites
- nvidia-docker2

## Usage
1. Enter downloaded repo
2. Run script `download_caffe.sh`
3. Run `docker build -t <your-image-name> .`
4. Run `docker run --runtime=nvidia -d -p 5000:5000 <your-image-name>`

Full description available at this [link](https://github.com/NVIDIA/nvidia-docker/wiki/DIGITS).

## Final words

Repo is used for my Master Thesis project.

