FROM ubuntu:18.04
WORKDIR /usr/src/app
COPY script2.bash .
RUN chmod +x script2.bash
RUN apt-get -o Acquire::Max-FutureTime=86400 update
RUN apt-get install -y curl
CMD ./script2.bash