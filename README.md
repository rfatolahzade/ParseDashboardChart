# ParseDashboardChart

Kube time:
```bash
git clone https://github.com/rfatolahzade/ParseDashboardChart.git
cd charts/parse-dashboard
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
https://rfatolahzade.github.io/ParseDashboardChart/index.html
```

helming!

```bash
helm repo add parse-dashboard https://rfatolahzade.github.io/ParseDashboardChart
helm install parse-dashboard parse-dashboard/parse-dashboard 
```
