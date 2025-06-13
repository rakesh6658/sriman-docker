ARG image
ARG TAG
FROM ${image}:${TAG}
ARG name
RUN echo "$name" > /tmp/name
RUN echo "$image" > /tmp/image
CMD ["/bin/bash", "-c", "cat name" ]