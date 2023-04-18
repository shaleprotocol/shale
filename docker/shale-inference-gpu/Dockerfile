FROM huggingface/transformers-inference:latest-cuda

RUN apt update && apt install -y openssh-server
RUN mkdir /var/run/sshd