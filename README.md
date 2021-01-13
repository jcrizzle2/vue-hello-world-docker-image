# Vue Hello World Docker Image

Runs a containerized version of the basic hello_world Node.js app at: [Vue CLI](https://cli.vuejs.org/guide/creating-a-project.html)

**To pull the ghcr.io/jcrizzleorg/vue-hello-world-docker-image image into your Docker environment run:**
```
- docker pull ghcr.io/jcrizzleorg/vue-hello-world-docker-image:latest
```

**To run the image in a container issue the following command:**
```
- docker run -it -p 8080:8080 --rm --name hello_world ghcr.io/jcrizzleorg/vue-hello-world-docker-image
```

**Please see link below for more information**
[Containerizing the VUE Hello World Node Application](https://github.com/jcrizzle2/vue-cli-docker-container)
