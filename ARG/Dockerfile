ARG version
FROM almalinux:${version:-9}
ENV COURSE="devops" \
    TRAINER="Siva Kumar"
ARG STUDENT="vidya"
ENV STUDENT=$STUDENT
RUN echo "Hi, Course is: ${COURSE}, trainer is: ${TRAINER}, student is: ${STUDENT}"
CMD ["sleep", "1000"]