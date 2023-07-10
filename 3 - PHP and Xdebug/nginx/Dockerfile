FROM nginx:alpine
COPY nginx/default.conf /etc/nginx/conf.d
RUN addgroup --gid 1024 mygroup
RUN adduser --disabled-password --gecos "" --force-badname --ingroup 1024 myuser 
USER myuser