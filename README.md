# mageckflute

Docker image for pooled CRISPR functional genetic screens with Jupyterlab.


## How to run 

```
docker run --interactive --tty --rm --name test_v1  -p 8889:8889 -it jupyterlab_mageckflute:0.0.0 jupyter-lab  --ip=0.0.0.0 --port=8889  --allow-root  --NotebookApp.token='123456' --no-browser
```

```
docker build -t jupyterlab-mageckflute:0.1.0 -f Dockerfile.0.1.0 .
docker tag jupyterlab-mageckflute:0.1.0 bix4oa/jupyterlab-mageckflute:0.1.0
docker push bix4oa/jupyterlab-mageckflute:0.1.0
```

## Release

- v0.1.1 

* mageck-vispr==0.5.4

* MAGeCKFlute-1.8.0


