FROM scratch
ADD alpine-minirootfs-3.12.0-x86_64.tar.gz /
ADD info.sh /
WORKDIR /
RUN chmod 700 /info.sh
CMD ["/bin/sh"]
CMD ["cd /"]
#CMD ["chmod +x info.sh"]
CMD ["./info.sh"]
LABEL maintainer="jkanda <jan.kanda@t-systems.com>"
LABEL version="1.0"
