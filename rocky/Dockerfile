FROM rockylinux:8.9

RUN dnf update -y && \
    dnf install -y \
            gcc \
            git \
            epel-release && \
    dnf install -y apptainer

#ENTRYPOINT ["/usr/bin/apptainer"]

