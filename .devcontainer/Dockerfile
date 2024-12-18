FROM python:3.12

COPY .devcontainer/ciscoumbrellaroot.crt /usr/local/share/ca-certificates/extra/ciscoumbrellaroot.crt
RUN update-ca-certificates
COPY python/requirements.txt /opt/install/
RUN pip3 install -r /opt/install/requirements.txt
