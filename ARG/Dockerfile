ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="docker" \
    TRAINER="shiva"
ENV COURSE=${COURSE}
RUN echo "Trainer = ${TRAINER}, Course = ${COURSE}, Version = ${VERSION}"
CMD ["sleep", "10000"]