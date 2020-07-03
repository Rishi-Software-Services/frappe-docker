ARG GIT_BRANCH=develop
FROM rishira1/frappe-worker:${GIT_BRANCH}

ARG GIT_BRANCH
RUN install_app erpnext https://github.com/Rishi-Software-Services/erpnext ${GIT_BRANCH}
