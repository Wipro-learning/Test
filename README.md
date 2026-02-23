This workspace includes a simple Docker Compose setup that runs the official NGINX image and serves static content from the `html/` folder.

Quick start (PowerShell):

```powershell
# From c:\Users\adity\gitTraining
docker compose up -d      # start the nginx container in detached mode
docker compose ps         # show running services
# open http://localhost:8080/ in your browser to see the sample page
# When done:
docker compose down       # stop and remove containers
```

If you don't have Docker Compose as a plugin, try `docker-compose` instead of `docker compose`.
