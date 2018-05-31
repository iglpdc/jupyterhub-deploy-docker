#ARG DOCKER_NOTEBOOK_IMAGE
#FROM $DOCKER_NOTEBOOK_IMAGE
FROM jupyter/datascience-notebook:c7fb6660d096
ARG JUPYTERHUB_VERSION
RUN python3 -m pip install --no-cache jupyterhub==$JUPYTERHUB_VERSION
