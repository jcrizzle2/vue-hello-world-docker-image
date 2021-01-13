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
- [Containerizing the VUE Hello World Node Application](https://github.com/jcrizzle2/vue-cli-docker-container)

**Creating a container from the image:**
If you wish the create a container out the image you can issue the following command:
```
- docker create --name hello-world-container -p 8080:8080 ghcr.io/jcrizzleorg/vue-hello-world-docker-image
```
The command above should allow the app to bind to all addresses.

**Starting the container:**
```
- docker start hello-world-container
```

**Accessing the app.**
The docker run command binds the application to 127.0.0.1 to port 8080. To view the Node application in a browser you can type: 
- [http://localhost:8080](*http://localhost:8080)
