ARG version
FROM almalinux:${version:-9}
ARG course="docker" \
    trainer="sivakumar" \
    duration="10hrs"
ENV course=${course} \
    duration=${duration} \
    trainer=${trainer}
RUN echo "Course is: ${course}, Duration is: ${duration}, Trainer is: ${trainer}, Version is: ${version}"