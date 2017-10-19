# data_viz

1. create conda virtual env (Python version >= 3.4)

2. Install jupyterhub
```
$ conda install -c conda-forge jupyterhub
$ conda install notebook
```

3. Test
```
$ jupyterhub -h
$ configureable-http-proxy -h
```

4.
```
$ pip install dockerspawner
$ docker pull jupyterhub/singleuser
```

```
jupyterhub --generate-config
```
https://www.youtube.com/watch?v=gSVvxOchT8Y
