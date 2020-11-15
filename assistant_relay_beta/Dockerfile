FROM apipa169/assistant-relay:3.2.0

ENV LANG C.UTF-8
ENV databasePath='/data/db.json'
ENV configurationPath='/data/config.json'
ENV jwtSecret='Assistant-Relay-2020'

LABEL \
    io.hass.name="Assistant Relay" \
    io.hass.description="Send (broadcast) commands to your Google Assistant via REST command" \
    io.hass.type="addon" \
    io.hass.version="3.2.0" \
    maintainer="Apipa169" \
    org.label-schema.description="Send (broadcast) commands to your Google Assistant via REST command" \
    org.label-schema.name="Assistant Relay" \
    org.label-schema.usage="https://github.com/Apipa169/Assistant-Relay-for-Hassio/blob/master/README.md" \
    org.label-schema.vcs-url="https://github.com/Apipa169/Assistant-Relay-for-Hassio"

CMD [ "/run.sh" ]
