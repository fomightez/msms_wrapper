#content from https://github.com/pyvista/pyvista-tutorial/tree/gh-pages/binder , with the exception of the `pip install -r binder_requirements.txt` line and installing curl
ARG BASE_IMAGE_TAG=latest
FROM ghcr.io/pyvista/pyvista:$BASE_IMAGE_TAG

COPY . ${HOME}
WORKDIR ${HOME}

RUN pip install -r binder_requirements.txt