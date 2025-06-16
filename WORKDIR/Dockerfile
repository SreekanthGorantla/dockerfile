FROM amazonlinux:9
RUN mkdir /tmp/work-dir-demo
WORKDIR /tmp/work-dir-demo
RUN pwd
RUN echo "hello formw WORK DIR" > hello.txt
CMD [ "sleep", "100" ]

# cd command will not work in docker. Here the command is WORKDIR <path>