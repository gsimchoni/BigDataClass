# Intro to DS @ TAU: Big Data Class

To use the Hadoop 2.7 Docker image: https://hub.docker.com/r/sequenceiq/hadoop-docker

(I recommend running from within the hadoop_example folder, mounting it after pulling and building it, using:

```
docker run -it -v ${PWD}:/home sequenceiq/hadoop-docker:latest /etc/bootstrap.sh -bash
```

)

Script we used in class: hadoop_example/hadoop_script
