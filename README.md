# AMPLAB - Sound retrieval with Freesound and creative applications

This repository includes the materials for the AMPLAB Freesound session and assignment.
Please follow the instructions below to set up the required software in your computer and be able to run the notebooks.


## 1) Install Docker

It is recommended to read the documentation about [Docker](https://docs.docker.com/)
and [docker-compose](https://docs.docker.com/compose/).

### Windows
https://docs.docker.com/docker-for-windows/install/

### Mac
https://docs.docker.com/docker-for-mac/install/

### Ubuntu
https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/#install-docker-ce

## 2) Install docker-compose

Follow [instructions](https://docs.docker.com/compose/install/).
Depending on your operartive system, this step won't be necessary because `docker-compose` will already have been installed in step 1).

## 3) Run the notebooks

Run the following command to startup the notebooks server:

    docker-compose up

Then access `http://localhost:8888` on your browser and when asked for a password use **mir**.

Form the interface that you'll see in your browser you can open the three included Jupyter Notebooks and follow them in order:

 1) Create source sound collection
 2) Analyze source collection and target file
 3) Reconstruct target file with source collection frames
 

If you reached this part of the README with no issues then you're ready for the session and for the assignment!
