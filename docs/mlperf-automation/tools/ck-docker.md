**[ [TOC](../README.md) ]**

You can use [adaptive CK containers](https://github.com/octoml/venv/blob/main/README.docker.md)
with the CK CLI as follows:

```
ck pull repo:octoml@venv
ck ls docker
ck build docker:ck-template-ml --tag=ubuntu-20.04
ck run docker:ck-template-ml --tag=ubuntu-20.04
```
