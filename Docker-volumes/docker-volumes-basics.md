# Basic Docker Volume Commands

## Introduction

Docker volumes are used to persist data generated by and used by Docker containers. This guide will cover the basic commands used to work with Docker volumes.

## Common Docker Volume Commands

### 1. `docker volume ls`

This command lists all the volumes created in Docker.

```bash
docker volume ls
```

### 2. `docker volume inspect`

This command displays detailed information about a specific volume.

```bash
docker volume inspect <volume_name>
```

### 3. `docker volume create`

This command creates a new volume.

```bash
docker volume create <volume_name>
```

### 4. `docker volume rm`

This command removes a volume.

```bash
docker volume rm <volume_name>
```

## Conclusion

By understanding these basic Docker volume commands, you can effectively manage and troubleshoot Docker volumes.
