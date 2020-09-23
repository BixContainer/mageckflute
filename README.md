# mageckflute

Docker image for pooled CRISPR functional genetic screens with Jupyterlab.


## How to run 

```
docker run --interactive --tty --rm --name test_v1  -p 8889:8889 -it jupyterlab_mageckflute:0.0.0 jupyter-lab  --ip=0.0.0.0 --port=8889  --allow-root  --NotebookApp.token='xie186' --no-browser
```

## Release

- v0.1.1 

* mageck-vispr==0.5.4

* MAGeCKFlute-1.8.0


