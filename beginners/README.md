# Beginners Track

# Introduction to Docker 

- [What is Docker?](https://github.com/collabnix/dockerlabs/blob/master/beginners/docker/what-is-docker.md)
- [Difference between Docker & Container](https://github.com/collabnix/dockerlabs/blob/master/beginners/docker/docker-vs-container.md)
- [What are Containers? What are they used for?](https://github.com/collabnix/dockerlabs/blob/master/beginners/linux-containers.md)
- [Difference between VM and Docker](https://github.com/collabnix/dockerlabs/blob/master/beginners/difference-docker-vm.md)
- [Similarity between VM and Docker](https://github.com/collabnix/dockerlabs/blob/master/beginners/similarity-vm-docker.md)
- [How is Container different from Virtual Machine?](https://github.com/collabnix/dockerlabs/blob/master/beginners/difference-vm-containers.md)
- [Top Reasons why to & why not to run Docker containers directly on Bare Metal System](https://github.com/collabnix/dockerlabs/blob/master/beginners/docker-on-bare-metal.md)
- [How is Docker Networking different from VM Networking](https://github.com/collabnix/dockerlabs/blob/master/beginners/difference-vmnetwork-docker-networking.md)
- [Understanding Docker Underlying Technologies]()
- [Can container communication cross over to noncontainerized apps?](https://github.com/collabnix/dockerlabs/blob/master/beginners/linux-comm-containers.md)
- [Architecture of Docker](https://github.com/collabnix/dockerlabs/blob/master/beginners/architecture-of-a-docker.md)
   - [Docker Enterprise Edition](https://github.com/collabnix/dockerlabs/blob/master/beginners/architecture-dockeree.md)
- [Docker Engine Release Features](https://github.com/collabnix/dockerlabs/blob/master/beginners/evolution-of-docker-platform.md)
   - [18.09](https://github.com/collabnix/dockerlabs/blob/master/beginners/1809.md)
   - [19.03 Community Edition](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/from-source/README.md#how-to-install-latest-docker-19030-beta-1-test-build)
     - [How to install latest Docker 19.03.0 Test Build](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/from-source/README.md#how-to-install-latest-docker-19030-beta-1-test-build)<br>
     - [Support for ```docker context```](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/from-source/README.md#support-for-docker-context)<br>
     - [Support for rootless Docker](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/from-source/README.md#testing-rootless-docker-under-docker-19030-beta-1)<br>
     - [Context Switching Made Simple for Swarm & Kubernetes in Docker 19.03.0](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/from-source/README.md#support-for-docker-context)<br>
     - [Test Drive --gpu option during docker CLI runtime on Docker 19.03.0 Beta 3](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/from-source/README.md#support-for---gpu-runtime-option-in-docker-19030-beta3)
    - [19.03 Enterprise Edition](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/from-source/README.md#how-to-install-latest-docker-19030-enterprise-beta-4-test-build)
   
             
# Installing, Upgrading & Maintaining Docker 

- Installing Docker on 
   - [Linux](https://github.com/collabnix/dockerlabs/tree/master/beginners/install)
   - [Windows](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/windows/docker-desktop-for-windows/README.md)
   - [Windows Server](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/windows/docker-on-windows/README.md)
   - [IoT Platform](https://github.com/collabnix/dockerlabs/tree/master/beginners/install/raspberrypi3)
     - [How to install Docker 18.09.0 on Raspberry Pi 3?](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/raspberrypi3/README.md)
     - [How to setup Docker Swarm Cluster on Raspberry Pi](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/raspberrypi3/setting-up-swarm-cluster.md)
     - [Building up K3s Cluster on Raspberry Pi 3 Nodes](https://github.com/collabnix/dockerlabs/blob/master/beginners/install/raspberrypi3/setting-up-k3s-cluster.md)
     - MacOS
- Compiling Your Own Docker Binary from Source
- Scripts & Installation Tools
- [Upgrading Docker from CE to EE](https://github.com/collabnix/dockerlabs/blob/master/beginners/upgrade-1809ce-1809ee/README.md)


# Docker Components

- [Docker Client-Server Architecture](https://github.com/collabnix/dockerlabs/tree/master/beginners/components/server_client.md)
- Docker Daemon
  - How to open Docker Daemon to External world?
  - Docker Daemon runs as root. How can Docker be secure?
- What is a Docker Image?
  - Building Your own Docker Image from Scratch
- What is Docker Container?
- Difference between Docker Image Vs Docker Container?
- What is Docker registry?
  - [Building a Private Docker Registry](https://github.com/collabnix/dockerlabs/blob/master/beginners/build-private-docker-registry.md)
  - [Building a Private Docker Registry using Portus](https://github.com/collabnix/dockerlabs/blob/master/beginners/portus/README.md)
- What is DockerHub?
  - Setting Up an Automated Build on Docker Hub for Continuous Integration/Deployment
  
# Working with Docker Image & Container

- [Running Hello World Example](https://github.com/collabnix/dockerlabs/blob/master/beginners/helloworld/README.md)
- [Working with Docker Image](https://github.com/collabnix/dockerlabs/blob/master/beginners/workingwithdockerimage.md) 
  - [Saving Images and Containers as Tar Files for Sharing](https://github.com/collabnix/dockerlabs/blob/master/beginners/saving-images-as-tar/README.md) 
  - [Versioning an Image with Tags](https://github.com/collabnix/dockerlabs/blob/master/beginners/versioning-an-image-with-tags/README.md)
- [Building Your First Alpine Docker Image and Push it to DockerHub](https://github.com/collabnix/dockerlabs/blob/master/beginners/building-your-first-alpine-container.md)
- [Building Docker Image from Scratch](https://github.com/collabnix/dockerlabs/blob/master/beginners/building-docker-image-from-scratch.md)
- [Working with Docker containers](https://github.com/collabnix/dockerlabs/blob/master/beginners/working-with-docker-containers/README.md)
  - [Detaching containers without stopping them](https://github.com/collabnix/dockerlabs/blob/master/beginners/deatching-containers-without-stopping-them/README.md)
- [Creating Docker Base Image](https://github.com/collabnix/dockerlabs/blob/master/beginners/create-base-image.md)
- [Build Your Own Docker Image](https://github.com/collabnix/dockerlabs/blob/master/beginners/building-you-own-docker-image/README.md)
  - [Using Packer to Create a Docker Image](https://github.com/collabnix/dockerlabs/blob/master/beginners/using-packer-to-create-a-docker-image/README.md)
  - [Using ONBUILD Images](https://github.com/collabnix/dockerlabs/blob/master/beginners/using-onbuild-images/README.md)
- [Creating Effective Docker Images](https://github.com/collabnix/dockerlabs/blob/master/beginners/b300/b304-creating-effective-docker-images.md)
- [Creating a DockerHub Account](https://github.com/collabnix/dockerlabs/blob/master/beginners/creating-a-dockerhub-account/README.md)
- [Sharing Your Docker Image](https://github.com/collabnix/dockerlabs/blob/master/beginners/sharing-your-docker-image/README.md)
  -  [Publishing Your Image to Docker Hub](https://github.com/collabnix/dockerlabs/blob/master/beginners/publishing-your-image-to-docker-hub/README.md)

  
 # Working with Dockerfile
 
- Building Docker Image from Dockerfile
  - Writing Your First Dockerfile
  - Injecting files into your image using ADD
  - Rebuilding without Cache 
  - Busting the Cache 
  - Reducing the size of your Dockerfile image. 
  - Packaging a Flask Application Inside a Container 
  - Optimizing Your Dockerfile by Following Best Practices 
- Reverse-engineer a Dockerfile from an image
- Using make with Docker
- [How is ENTRYPOINT instruction under Dockerfile different from RUN instruction?](https://github.com/collabnix/dockerlabs/blob/master/beginners/dockerfile/entrypoint-vs-run.md)
- [Difference between Docker Compose Vs Dockerfile](https://github.com/collabnix/dockerlabs/blob/master/beginners/difference-compose-dockerfile.md)
- [How to use ARG to pass enviornmental variable at runtime](https://github.com/collabnix/dockerlabs/blob/master/beginners/dockerfile/arg-dockerfile-runtime.md)

# Getting Started with Docker Volume

[Creating Volume Mount from Dockerfile](https://github.com/collabnix/dockerlabs/blob/master/beginners/volume/create-a-volume-mount-from-dockerfile.md)<br>
[Managing volumes through Docker CLI](https://github.com/collabnix/dockerlabs/blob/master/beginners/volume/managing-volumes-via-docker-cli.md)<br>
[Creating Volume Mount from **docker run** command & sharing same Volume Mounts among multiple containers](https://github.com/collabnix/dockerlabs/blob/master/beginners/volume/creating-volume-mount-from-dockercli.md)<br>
[Mounting host directory into container](https://github.com/collabnix/dockerlabs/blob/master/beginners/volume/bind-mounts.md)<br>
[Creating Volume with Alpine OS](https://github.com/collabnix/dockerlabs/blob/master/beginners/volume/Creating%20Volume%20with%20alphine.md)<br>

# FAQs

[How to Run Multiple Python Versions on a Docker Host System]()
  




 [Proceed >> What is Docker?](https://github.com/collabnix/dockerlabs/blob/master/beginners/docker/what-is-docker.md)





