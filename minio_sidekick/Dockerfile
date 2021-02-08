# 0.5.8
FROM minio/sidekick:v0.5.8
MAINTAINER ljp
ENV SIDEKICK_CACHE_ACCESS_KEY minio
ENV SIDEKICK_CACHE_SECRET_KEY Nsoas123!
CMD --health-path=/minio/health/live --address :8080 http://minio-node{01...04}:9000
