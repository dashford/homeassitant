FROM eclipse-mosquitto:1.6.13

ARG USERNAME
ARG PASSWORD

ENV USERNAME ${USERNAME}
ENV PASSWORD ${PASSWORD}

RUN mosquitto_passwd -c -b /mosquitto/config/passwd "${USERNAME}" "${PASSWORD}"