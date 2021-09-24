FROM registry.gitlab.com/atlantic-crypto/kubevirt/virt-launcher:60c51f5ce866dd4c3abdec40d41fc5999858848b

RUN mv /usr/libexec/virtiofsd /usr/libexec/virtiofsd.bin

COPY virtiofsd-wrapper /usr/libexec/virtiofsd

RUN chmod +x /usr/libexec/virtiofsd
