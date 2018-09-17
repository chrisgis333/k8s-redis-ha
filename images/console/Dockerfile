FROM python:3.5.3

ADD ["https://github.com/chrisgis333/dig-a/releases/download/v1.0.1/dig-a_linux_amd64", "/dig-a"]
ADD ["https://github.com/chrisgis333/dig-srv/releases/download/v1.0.0/dig-srv_linux_amd64", "/dig-srv"]

RUN apt-get update && apt-get install -y bc dnsutils redis-tools
RUN pip install redis ipython

CMD ["sleep", "infinity"]
