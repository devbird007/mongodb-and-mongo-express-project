# mongodb-and-mongo-express-project
This is a simple demo project deploying mongodb and mongo-express on a minikube cluster to demonstrate the power of kubernetes yaml manifests

![mongo](https://user-images.githubusercontent.com/100073682/230692463-0b74ae1f-f290-49b9-992f-d11de12a0043.png)

A request is sent from the browser to the mongo-express external service component which is then forwarded to the mongo-express pod both built with the
`mongo-express.yaml` kubernetes manifest.

The 

A kubernetes secret file not uploaded to this repository contains the root admin username and password that allows mongo-express to access
the mongodb container
