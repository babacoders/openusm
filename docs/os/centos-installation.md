# Installing Docker on CentOS 7

## Update the package database:

```
sudo yum check-update
```

## Add the official Docker repository, download the latest version of Docker, and install it:

```
curl -fsSL https://get.docker.com/ | sh
```

## Start the Docker daemon:

```
sudo systemctl start docker
```

## Verify that Docker is running fine:

```
sudo systemctl status docker
```
