FROM centos
RUN curl -O https://releases.hashicorp.com/terraform/0.12.19/terraform_0.12.19_linux_amd64.zip
RUN yum install unzip -y && unzip terraform_0.12.19_linux_amd64.zip && mv terraform /bin