FROM n8nio/runners:2.13.3

USER root

RUN cd /opt/runners/task-runner-python && \
    uv pip install pandas openpyxl python-pptx

COPY n8n-task-runners.json /etc/n8n-task-runners.json

USER runner
