FROM postgres

#RUN mkdir /usr/myapp
ENV POSTGRES_USER postgres
ENV POSTGRES_PASSWORD postgres
ENV POSTGRES_DB postgres

COPY ./init-db/ /docker-entrypoint-initdb.d/
WORKDIR /docker-entrypoint-initdb.d/

EXPOSE 5432 
# ENTRYPOINT [ "sh", "-c", "cat init.sql" ]
