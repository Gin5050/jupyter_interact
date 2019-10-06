# memo

```
docker run --runtime=nvidia -it -v /home/yuki/work/jupyter_interactive:/workspace/work -p 8888:8888 -p 6006:6006 jupyter_interactive
```

```
jupyter notebook --ip=0.0.0.0 --no-browser --allow-root
```

```
tensorboard --logdir=./logs