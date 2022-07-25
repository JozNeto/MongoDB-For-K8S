### 1 - kubectl apply -f mongo-secrets.yaml
### 2 - kubectl create -f mongo-pvc.yaml
### 3 - kubectl apply -f mongodb-deployment.yaml
### 4 - kubectl create -f mongodb-nodeport-svc.yaml
### 5 - kubectl create -f mongodb-client.yaml

### mongo --host <ip> --port <port of nodeport svc> -u adminuser -p password123