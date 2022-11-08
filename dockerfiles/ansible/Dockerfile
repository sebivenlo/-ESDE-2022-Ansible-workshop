FROM ubuntu

RUN apt update;\
    apt -y install openssh-client;\
    apt -y install python3;\
    apt -y install python3-pip;\
    apt install -y sshpass
    
RUN pip3 install ansible;\
    ansible --version

    