ARG IMAGE_TAG=frappe-worker
ARG DOCKER_REGISTRY_PREFIX=valuefabric/oxytrack
FROM ${DOCKER_REGISTRY_PREFIX}:${IMAGE_TAG}

ARG GIT_REPO=https://github.com/oxytrack/erpnext
ARG GIT_BRANCH=version-13

RUN install_app erpnext ${GIT_REPO} ${GIT_BRANCH}
