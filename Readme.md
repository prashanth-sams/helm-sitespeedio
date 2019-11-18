# Helm sitespeedio

## Installation
Create Helm release for `sitespeedio` and `graphite`
```
helm install --name sitespeedio sitespeedio/ --namespace=sitespeed-io
helm install --name graphite graphite/ --namespace=sitespeed-io
```

## Notes
replace `www.hackme.com` with your hostname in graphite `values.yaml`

> ### More info.
https://gist.github.com/prashanth-sams/02b560c3ff9270a9b2b019842444e949