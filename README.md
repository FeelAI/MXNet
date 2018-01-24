# MXNet

## Install

- Linux
- Python
- CPU
- Docker

```shell
$ docker pull mxnet/python

$ docker images

$ docker run -it mxnet/python bash

root@4919c4f58cac:/# python

>>> import mxnet as mx
>>> a = mx.nd.ones((2, 3))
>>> b = a * 2 + 1
>>> b.asnumpy()
array([[3., 3., 3.,],
       [3., 3., 3.]], dtype=float32)
>>>exit()
root@4919c4f58cac:/# exit
```

> - libdc1394 error: Failed to initialize libdc1394
> sudo ln /dev/null /dev/raw1394


