# INFRION – DevOps & Cloud Solutions

## Run locally
npm install
npm run dev

## Docker
docker build -t infrion/web:1.0 .
docker run -p 8080:80 infrion/web:1.0

## Kubernetes
kubectl apply -f k8s/
