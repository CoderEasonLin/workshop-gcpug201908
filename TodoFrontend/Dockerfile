#
# http static server one-liners
#

FROM busybox:1.30

WORKDIR /app
COPY . .
RUN chmod +x run.sh


# Configurable host:port - location of backend todoapi server
ENV TODOAPI_HOST localhost
ENV TODOAPI_PORT 30080

EXPOSE 80
CMD ["sh", "run.sh"]