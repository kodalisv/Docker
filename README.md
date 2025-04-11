# Docker Text Analysis Project

## Overview

This project demonstrates the use of Docker for running a Python script that analyzes text files inside a container. It includes setting up Docker Desktop, building a Dockerfile with a lightweight base image, and performing multiple text processing tasks within the container environment.

## Objectives

1. Install Docker Desktop on your machine (Windows/macOS/Linux).
2. Run Docker Desktop and submit a screenshot showing the container running.
3. Create a Dockerfile using a lightweight base image (e.g., python:3.9-slim).
4. Develop a Python script that:
   - Reads two text files from `/home/data`.
   - Performs word count and frequency analysis.
   - Identifies the machine's IP address.
   - Writes results to `/home/data/output/result.txt`.
   - Prints result.txt contents on execution.

5. Optimize the Docker image to be under 200MB.
6. Package the final image into a tar file named after your email username (e.g., `yourusername.tar`).

## Directory Structure

