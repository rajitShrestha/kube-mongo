```bash
This project is used to deploy the mongo and express docker image to a kubernetes cluster usinng kops.
docker image: 
  - mongo: https://hub.docker.com/_/mongo
  - mongo-express: https://hub.docker.com/_/mongo
Setup:
  - Setup your hosted zone in AWS route 53 using domain name(Godady)
  - Setup a kops cluster in cloud VM or a local machine
  - Run the command "kubectl apply -f /path/to/your/yaml/directory"
```
