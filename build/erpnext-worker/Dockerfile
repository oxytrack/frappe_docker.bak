ARG IMAGE_TAG=erpnext-worker
ARG DOCKER_REGISTRY_PREFIX=valuefabric/oxytrack
FROM ${DOCKER_REGISTRY_PREFIX}:${IMAGE_TAG}

ARG GIT_REPO=https://github.com/wtwong316/erpnext
ARG GIT_BRANCH=version-13

RUN install_app erpnext ${GIT_REPO} ${GIT_BRANCH}
