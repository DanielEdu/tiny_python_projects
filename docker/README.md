# Tiny Python Projects Docker

If you like, you can run and test all the code using Python 3.8.3 in a Docker image:

```
docker build -t tiny_python_projects .

docker run -it --rm -d -v c:/Users/danie/PROJECTS/tiny_python_projects:/app tiny_python_projects bash
```
