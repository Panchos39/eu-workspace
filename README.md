# eu-workspace
For launching application in docker environment, you should use https://github.com/Panchos39/eu-workspace-environment-docker repository in the same folder, where eu-workspace was placed
When you placed eu-ai-environment-docker in the same folder, as eu-workspace, to start jupyter-lab session, you have to use following command
```
docker-compose build
```

```
docker-compose up --build --force-recreate --remove-orphans -d && \
docker-compose logs -f --tail 100
```
These commands will build docker-container and launch jupyter-lab session with all required libs ready to use
