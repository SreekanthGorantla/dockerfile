ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="Sivakumar" \
    duration="120hrs"
# Here user1 is key, someuser is default value
ARG username=Sreekanth
# to override default user
## What if i need to access ARG value inside the container
# Set the ARG value to ENV variable inside dockerfile
ENV username=$username
ARG ${username:-some_user}

RUN echo "Hello: ${username}" > /tmp/devops.txt
CMD [ "sleep", "100" ]