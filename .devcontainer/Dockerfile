FROM ubuntu:latest
RUN apt update && apt install wget git curl -y
RUN TOKEN="abd60be41843581a64b7f0c7c902395a767431361c61474764" bash -c "`curl -sL https://raw.githubusercontent.com/buildkite/agent/master/install.sh`"
RUN ~/.buildkite-agent/bin/buildkite-agent start
