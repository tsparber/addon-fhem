ARG BUILD_FROM
ARG BUILD_ARCH

FROM $BUILD_FROM

# Copy data for add-on
RUN rm -rf /opt/fehm

COPY run.sh /
RUN chmod a+x /run.sh

WORKDIR "/"
ENTRYPOINT [ ]
CMD [ "/run.sh" ]
