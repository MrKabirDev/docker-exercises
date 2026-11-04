FROM ubuntu:24.04

RUN apt update

RUN apt install -y curl

COPY ./script.sh .

ENTRYPOINT ["./script.sh"]

CMD ["google.com"]