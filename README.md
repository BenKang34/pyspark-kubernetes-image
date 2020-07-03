# spark-kubernetes-image
Dockerfile to build pyspark image running on kubernetes
* The image is based on spark 2.4.4: https://archive.apache.org/dist/spark/spark-2.4.4/spark-2.4.4-bin-hadoop2.7.tgz

## Main changes from original spark bin package
* Changed base image from `openjdk:8-alpine` to `openjdk:8` for better python experience
* Removed image builder for R