FROM scratch
LABEL maintainer="luky <lukas.zavatzky@gmail.com>"
ADD alpine-minirootfs-3.13.5-x86_64.tar.gz /
LABEL description="moj novy image na matrix ukazku"

RUN apk add cmatrix
CMD ["/usr/bin/cmatrix"] -o
