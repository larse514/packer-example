# Encyrpted EBS volumes for EC2 AMI

## Running the example
This project uses a tool called [batect](https://github.com/charleskorn/batect) to run the application.  It uses a docker container to create a portable build environment.  In order to run the sample Packer template simply ensure docker is running on your machine and run either of the following commands:

Packer Validate:
```
./batect validate
```

Packer Build:
```
./batect build
```

You can also choose to install Packer [manually](https://www.packer.io/intro/getting-started/install.html) or via [brew](https://formulae.brew.sh/formula/packer).  Full instructions can be found on the Packer [home page](https://www.packer.io/intro/getting-started/install.html).

Additionally you may use the offical DockerHub [image](https://hub.docker.com/r/hashicorp/packer/)