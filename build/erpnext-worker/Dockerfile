ARG IMAGE_TAG=v0.0.1
ARG DOCKER_REGISTRY_PREFIX=localhost:5000
FROM ${DOCKER_REGISTRY_PREFIX}/frappe-worker:${IMAGE_TAG}

ARG GIT_REPO=https://github.com/wtwong316/erpnext
ARG GIT_BRANCH=version-13

RUN install_app erpnext ${GIT_REPO} ${GIT_BRANCH}
