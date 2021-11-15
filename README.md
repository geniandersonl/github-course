# Git Course

Este é um repositório teste para ensinar como o Git funciona.

# Primeira coisa a ser feita é instalar o git
# Instalando as dependencias
sudo apt update
sudo apt install libz-dev libssl-dev libcurl4-gnutls-dev libexpat1-dev gettext cmake gcc

# Instalando git ubuntu 20.04
mkdir tmp
cd /tmp
curl -o git.tar.gz https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.26.2.tar.gz
tar -zxf git.tar.gz
cd git-*
make prefix=/usr/local all
sudo make prefix=/usr/local install
exec bash

# Verificando a versao do git
git --version



# Definindo editor do git
git config --global  user.name "user"
git config --global  user.mail "email"
git config --global  core.editor "name-editor"

# Pegar chave configurada
git config user.name  
git config user.email
git config core.editor
