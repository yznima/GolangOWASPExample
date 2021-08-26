FROM owasp/dependency-check:6.2.2

# Have to override this because of filesystem permission issues with Gihtub Actions.
# The original dependency-check docker image overrides the USER which prevents the processes
# to be able to write to the filesystem. Thus, set it to root again.
# See https://docs.github.com/en/actions/creating-actions/dockerfile-support-for-github-actions#user
USER root