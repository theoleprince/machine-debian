FROM ubuntu:20.04
RUN mkdir -p /playbooks
RUN chmod 777 -R /playbooks
RUN apt-get update && \
    apt-get install nano sudo -y && \
    apt-get install curl sudo -y && \
    apt-get install software-properties-common sudo -y && \
    apt-get install ansible sudo -y && \
    apt-get install net-tools sudo -y && \
    apt-get install -y iputils-ping
RUN apt-get install -y openssh-client
RUN apt-get install -y python3

    #  && \
    # apt-get install -y openssh-clients python3 && \
    # apt-get install nano sudo -y && \
    # apt-get install curl sudo -y && \
    # apt-get install software-properties-common sudo -y && \
    # apt-get install ansible sudo -y
CMD tail -f /dev/null


