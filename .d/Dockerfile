FROM docker.nih/block:dnsmasq

ARG CACHE

RUN source .bashrc && block compile service && ln -nfs ../sv/consul-agent service/
