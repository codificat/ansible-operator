FROM quay.io/shawn_hurley/ansible-operator

COPY busybox/ /opt/ansible/roles/busybox/
COPY playbook.yaml /opt/ansible/playbook.yaml
COPY config.yaml /opt/ansible/config.yaml

RUN adduser ansible-operator
USER ansible-operator
