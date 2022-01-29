# DashboardParse
```bash
 docker-compose up
 ```
 ```bash
mkdir dashboard
cd dashboard
cp ../docker-compose.yaml .
kompose convert
rm docker-compose.yaml
```

Kube time:
```bash
kubectl apply -f .
```