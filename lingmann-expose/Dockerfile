FROM stackbrew/ubuntu:14.04
MAINTAINER 98nmp5992z@snkmail.com

RUN apt-get update && apt-get -y install python
RUN echo "expose" > index.html
EXPOSE 8000
ENTRYPOINT ["/bin/bash", "-c"]
CMD ["python", "-m", "SimpleHTTPServer"]
