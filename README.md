# docker
Repository for running Ski Planner in containerized docker environment

![Untitled-2024-03-07-1031](https://github.com/SW6-G6-2024/docker/assets/92527083/4b908f6f-5a79-42db-b310-33b14d9ff823)


## Ports

Front-end: 3000
Back-end: 8888
Route-generation: 3500
AI-rating-prediction: 1337

## Folder structure
Follow this folder structure

```
root
├── docker
|     └── Dockerfile
├── AI-rating-prediction
|     └── Dockerfile
├── Route-generation
|     └── Dockerfile
├── Ski-Planner-FE
|     └── Dockerfile
└── Ski-Planner-BE
      └── Dockerfile
```

## Command to run docker
```
docker-compose up --build
```

## Changing names of repos
If you have a different folder structure, you can change each path in the .env file.

## MongoURI error
To fix the mongo URI error, ensure that you have an .env file with the mongo uri, in the config folder of the Ski-Planner-BE repository
