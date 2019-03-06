FROM mesosphere/aws-cli:1.14.5

RUN apk --no-cache add jq

ADD scripts /root
ADD dummydata /dummydata

WORKDIR /root

ENTRYPOINT [ "/bin/sh", "-c", ". /root/s3-env; sh" ]
