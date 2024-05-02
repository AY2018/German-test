Les commandes : 

Création de l'image : 
Naviguer vers Dossier contenant le fichier dockerfile 

```bash
docker build -t ayoub2024/genie_app2:latest .
```
Push image vers docker hub 

```bash
docker push ayoub2024/genie_app2:latest
```
Aller sur docker hub pour tester : 

Pull et run image du docker hub pour tester : [https://hub.docker.com/]

```bash
docker run -p 8000:8000 -p 80:80 ayoub2024/genie_app2:latest
```

Aller sur : `http://localhost:8000/`