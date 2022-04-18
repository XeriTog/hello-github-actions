FROM debian

ADD entrypoint.sh /entrypoint.sh
RUN chomd +x /entrypoint.sh
ENTRYPOINT [ "/entrypoint.sh" ]