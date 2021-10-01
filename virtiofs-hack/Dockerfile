ARG BASE_IMAGE_TAG=latest
FROM registry.gitlab.com/atlantic-crypto/kubevirt/virt-launcher:${BASE_IMAGE_TAG}

RUN mv /usr/libexec/virtiofsd /usr/libexec/virtiofsd.bin

COPY virtiofsd-wrapper /usr/libexec/virtiofsd

RUN chmod +x /usr/libexec/virtiofsd
