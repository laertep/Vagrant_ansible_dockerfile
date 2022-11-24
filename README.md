# Projeto - Vagrant_ansible_dockerfile

* Instalação do vagrant na maquina VM plataforma linux;
* Instalação do update e do pacote ansible via inline pelo arquivo Vagranfile;


## Configuração do Ansible/VM
* Criação da role - docker compondo a instalação do docker;
* Criação da role - roles/docker-container/tasks para buildar a imagem criada pelo Dockerfile com aplicação NGINX;
* Criação da role - roles/docker-container/files para comportar o arquivo Dockerfile com a imagen do NGINX
