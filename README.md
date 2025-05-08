# DevOps 10 Deployment Cloud

## URL

| App-Name | Repo URL | Docker Hub URL |
| -------- | ------- | ------- |
| DevOpsXYZ | https://hub.docker.com/repository/docker/mosazhaw/node-web-app/general | https://github.com/devopszhaw/DevOps-10-Deployment-Cloud |

## Lernjournal


Als erstes habe ich mich mit meinem Azure Account angemeldet und die Ressource dop-helloworld erstellt.
(![loginAzure](images/loginAzure.png))

dannach die App auf Azure uploaded: 
(![UploadAzure](images/UploadAzure.png))

(![AppOnAzureURL](images/AppOnAzureURL.png))


Als nächstes habe ich die Applikation in einem Web-App-Container gestartet: 
(![WebContainer](images/WebContainer.png))

Hier die Logs:
(![AzureContainerLogs](images/AzureContainerLogs.png))

Ich habe die Devops Pipeline für mein Projekt gestartet und gesehen, dass ich zuerst die Tokens für den Docker-Hub Zugang erfassen muss 
(![noToken](images/noToken.png))

Das habe ich dann hier erstellt: 
(![CredentialsDockerHub](images/CredentialsDockerHub.png))

Als weiteres die Docker-Build.yaml Datei hinzugefügt: 
(![Docker-BuildYaml](images/Docker-BuildYaml.png))



