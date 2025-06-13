ARG image=ubuntu
ARG TAG=23.04
FROM ${image}:${TAG}
ARG name
RUN echo "$name" > /tmp/name
RUN echo "$image" > /tmp/image
CMD ["/bin/bash", "-c", "cat /tmp/name" ]