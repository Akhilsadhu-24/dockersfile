FROM almalinux
ARG username
RUN adduser $Akhil
USER $username
ARG COURSE
ARG TRAINER
RUN echo "Course: ${COURSE}, Trainer: ${TRAINER}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD ["sleep",'100']
