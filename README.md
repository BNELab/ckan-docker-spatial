<h1 align="center">CKAN Docker Compose - Open Data & GIS</h1>
<p align="center">
<a href="https://github.com/OpenDataGIS/ckan"><img src="https://img.shields.io/badge/Docker%20CKAN-2.9.8-brightgreen" alt="CKAN Versions"></a>


<p align="center">
    <a href="#overview">Overview</a> •
    <a href="#building-and-pushing-the-images">Building and Pushing the images</a> •
    <a href="#scanning-the-images-for-vulnerabilites">Scanning the images for vulnerabilites</a>
</p>

**Requirements**:
* [Docker](https://docs.docker.com/get-docker/)

## Overview
Contains CKAN spatial images for the different components of CKAN Cloud and a Docker compose environment (based on [the Git repo of the official Docker images](https://github.com/ckan/ckan-docker-base)) for development and testing Open Data portals.

>**Warning**:<br>
>This is a **custom base images of CKAN** with specific extensions for spatial data. For the official Git Repo, please have a look: [Pre-configured CKAN Docker images](https://github.com/ckan/ckan-docker-base).

# Pre-configured CKAN Docker images

The images will usually be used as a Docker Compose install in conjunction with other Docker images that make up the CKAN platform. 

The custom CKAN Docker installation (with Spatial extensions) can be found here: [ckan-docker](https://github.com/mjanez/ckan-docker)

The following CKAN versions are available at this repo:

| CKAN Version | Type | Docker tag | Notes |
| --- | --- | --- | --- |
| 2.9.8 | custom image | [`ghcr.io/mjanez/ckan-base-spatial:ckan-2.9.8`](https://github.com/users/mjanez/packages/container/ckan-base-spatial/85367720?tag=ckan-2.9.8) | Includes dependencies for spatial capabilities. Compatible with ckanext-spatial. |
| master | custom image | [`ghcr.io/mjanez/ckan-base-spatial:master`](https://github.com/users/mjanez/packages/container/ckan-base-spatial/85367720?tag=latest) | Latest version. Includes dependencies for spatial capabilities. Compatible with ckanext-spatial. |

### Building and Pushing the images

The images can be built locally and tagged appropriately.


### Scanning the images for vulnerabilites

<to do - provide details on the process of how we scan images - probably using [Synk Advisor](https://docs.docker.com/develop/scan-images/)>
