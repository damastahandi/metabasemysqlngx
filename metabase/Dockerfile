FROM metabase/metabase
MAINTAINER damasta.hairullah@gmail.com

COPY ./metabase/app/plugins/ojdbc6-11.1.0.6.0.jar /app/plugins/ojdbc6-11.1.0.6.0.jar

RUN chmod -R 777 /app/plugins

ENV MB_PLUGINS_DIR=/app/plugins