# ParseDashboardChart
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

Create a new branch for github pages:
```bash
#Create a new branch:
git checkout --orphan gh-pages
#We have to make it empty:
git rm -rf .
#Commit & Push the new branch:
git commit --allow-empty -m "root commit"
git push origin gh-pages
```
visit:
```bash
https://rfinland.github.io/ParseDashboardChart/index.html
```

helming!

```bash
helm repo add parse-dashboard https://rfinland.github.io/ParseDashboardChart
helm install parse-dashboard parse-dashboard/parse-dashboard 
```
