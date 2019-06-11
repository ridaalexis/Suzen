FROM bash

RUN apk add file 

RUN adduser -D suzen
USER suzen

ADD hello /bin/hello
WORKDIR /home/suzen


COPY .archive ./

ENTRYPOINT ["/bin/hello"]


#Solution
#echo -e `cat .hidden | sed 's/../\\\\x&/g'`

