# docker
Repository for running Ski Planner in containerized docker environment

## Folder structure
Follow this folder structure

```
root
├── docker
|     └── Dockerfile
├── Algorithm-Performance-improver
|     └── Dockerfile
├── Ski-Planner-FE
|     └── Dockerfile
└── Ski-Planner-BE
      └── Dockerfile
```

## Command to run docker
```
docker-compose up
```

## Changing names of repos
If you have a different folder structure, you can change each path in the .env file.

## MongoURI error
To fix the mongo URI error, ensure that you have an .env file with the mongo uri, in the config folder of the Ski-Planner-BE repository
