FROM confluentinc/cp-kafka:latest

USER root

RUN yum update -y && yum install -y \
    curl \
    nano \
    jq \
    && yum clean all

USER appuser

WORKDIR /opt/kafka

CMD ["sleep", "infinity"]
