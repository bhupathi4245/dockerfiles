ARG version
FROM almalinux:${version:-9}
ENV COURSE="DevOps" \
    DURATION="120HRS"
ARG TRAINER="SIVAKUMAR"
ENV TRAINER=${TRAINER}  # One way to access ARG instruction accessed from container during RUN TIME.
RUN echo "Hi, Course is: ${COURSE}, duration is: ${DURATION}, trainer is: ${TRAINER}"
CMD ["sleep", "1000"]