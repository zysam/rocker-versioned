FROM sysamlam/r:f-base

LABEL maintainer="sysamlam"

RUN mkdir -p /srv/shiny-server/koala_dashboard
WORKDIR /srv/shiny-server
ADD . .

RUN install2.r --error \
  -r "https://mirrors.tuna.tsinghua.edu.cn/CRAN/" \
  `cat pkgs.txt`



