FROM scratch
ADD alpine-minirootfs-3.12.0-x86_64.tar.gz /

LABEL mainteiner="jkanda"
LABEL description="Simple Matrix script"
RUN ["apk","add","cmatrix"]

CMD ["cmatrix"]
