ARG version
FROM almalinux:${version:-9}
ARG course="devop engineer" \
    duration="120 hours"
ENV duration=$duration
RUN echo "course: $course, duration: $duration"
CMD ["sleep","200"]