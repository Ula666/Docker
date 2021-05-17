# Docker
- is a containerisation platform
- can work with any OS
- creates containers and networks
- docker is faster than VM and smaller in size, and easily integrated in any system
- Docker is an open source platform for building, deploying, and managing containerized applications.

### Advantages:
- self-healing
- load balancing
- auto scaling

### What is containerization?
- Containerization allows developers to create and deploy applications faster and more securely.
-  It involves encapsulating or packaging up software code and all its dependencies so that it can run uniformly and consistently on any infrastructure. 

### What is Kubernetes?
- Kubernetes — also known as “k8s” or “kube” — is a container orchestration platform for scheduling and automating the deployment, management, and scaling of containerized applications.

### Why use containers?
- Containers offer all the benefits of VMs, including application isolation, cost-effective scalability, and disposability. But the additional layer of abstraction (at the OS level) offers important additional advantages:
- **Lighter weight:** Unlike VMs, containers don’t carry the payload of an entire OS instance—they include only the OS processes and dependencies necessary to execute the code.
- **Greater resource efficiency:** With containers, you can run several times as many copies of an application on the same hardware as you can using VMs. This can reduce your cloud spending.
- **Improved developer productivity:** Compared to VMs, containers are faster and easier to deploy, provision, and restart. This makes them ideal for use in continuous integration and continuous delivery (CI/CD) pipelines and a better fit for development teams adopting Agile and DevOps practices.


### DockerFile
- Every Docker container starts with a simple text file containing instructions for how to build the Docker container image. DockerFile automates the process of Docker image creation. It’s essentially a list of commands that Docker Engine will run in order to assemble the image.

### Docker images
- Docker images contain executable application source code as well as all the tools, libraries, and dependencies that the application code needs to run as a container. When you run the Docker image, it becomes one instance (or multiple instances) of the container.


