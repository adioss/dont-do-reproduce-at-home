# dont-reproduce-at-home

Repo to build a docker image with fake sensitive data in a layer (for testing purpose)

```
docker build --no-cache -t adioss/dontreproduceathome .
```

## Push image without changes
```
git commit --allow-empty -m 'fix: redeploy docker images'
git push  
```