# Hello World with Docker and Kubernetes

This repo consists of a Hello World Http backend App and Cron job of Hello World which runs after every 30 minutes. 
It shows:
   1. Run and test the application from Azure CLI
   2. Use ```strm/helloworld-http:latest``` docker image
   3. Create Kubernetes deployment and test it

It shows ```Hello from <hostname>``` for every request, making it easier to determine what host received the request.

## Kubernetes
 ## Create Deployment
        kubectl apply -f deployment.yaml
		
  ## Test Application
        curl http://localhost:8080
		
## Cron Job
 ## Create Deployment
        kubectl apply -f Cronjob_helloWorld.yaml
  
 ## Test Cron Job 
        kubectl get cronjob HelloApp


Please refer to document answer sheet for more details.
