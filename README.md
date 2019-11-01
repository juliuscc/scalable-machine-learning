# Scalable Machine Learning and Deep Learning

## Install environment

*Step 1:*

Pull the images by running

```sh
scripts/pull_images.sh
```

*Step 2:*

Run the image the first time

```sh
docker run -it --name jupyter-spark -p 8888:8888 jupyter/all-spark-notebook
```

or

```sh
docker run -it --name tensorflow -p 8888:8888 jupyter/tensorflow-notebook
```

## Stop and Start the Containers

The containers can be stopped and started. Everything will be saved.

To kill a container run

```sh
docker kill jupyter-spark
```

or

```sh
docker kill tensorflow
```

To start a container again run

```sh
docker start jupyter-spark -i
```

or

```sh
docker start tensorflow -i
```

