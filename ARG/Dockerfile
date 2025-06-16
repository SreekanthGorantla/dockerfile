ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="Sivakumar" \
    duration="120hrs"
# Here user1 is key, someuser is default value
ARG username=Sreekanth
# to override default user
ENV username=$username
ARG ${username:-some_user}

RUN echo "Hello User: ${username}" > /tmp/devops.txt
CMD [ "sleep", "100" ]