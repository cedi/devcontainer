# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.137.0/containers/go/.devcontainer/base.Dockerfile
ARG VARIANT="1"
FROM mcr.microsoft.com/vscode/devcontainers/go:0-${VARIANT}

RUN export GO111MODULE=on
RUN go get -u github.com/cweill/gotests/...
RUN go get -u golang.org/x/tools/cmd/benchcmp
RUN go get -u golang.org/x/lint/golint
RUN go get -u github.com/fzipp/gocyclo/cmd/gocyclo
RUN go get -u github.com/amitbet/gorename
