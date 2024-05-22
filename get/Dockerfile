ARG BUILD_FROM
FROM $BUILD_FROM

RUN \
    wget -O /get-hacs https://raw.githubusercontent.com/hacs/get/main/get \
    && chmod +x /get-hacs

CMD ["bash", "/get-hacs"]
