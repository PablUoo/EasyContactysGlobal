<h1>Projeto de Lista de Contatos Com Ruby on Rails</h1>

<p> Ruby 2.7.0</p>
<p> Rails 5.2.2</p>
<p> Nodejs -v atual</p>
<p>-------------------------</p>

Instalar o git:
```sh
sudo apt-get update
sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev libxml2-dev libxslt1-dev libcurl4-openssl-dev software-properties-common libffi-dev
```

Instalar o rbenv:
```sh
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
exec $SHELL
git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc
exec $SHELL
rbenv version
```

Instalar o Ruby:
```sh
rbenv install 2.6.1
ruby -v
rbenv global 2.6.1
```

Instalar bundler gem (gerenciador de dependências):
```sh
gem install bundler
rbenv rehash
```

Configurando Git:
```sh
git config --global color.ui true
git config --global user.name "seu nome aqui"
git config --global user.email "seuemail@example.com"
```

Gerando chaves ssh e copiando conteúdo:
```sh
ssh-keygen -t rsa -b 4096 -C "seuemail@example.com"
cat ~/.ssh/id_rsa.pub
ssh -T git@github.com
```

Instalando o Rails:
```sh
gem install rails -v 5.2.2
rails -v
```

Instalando o PostgreSQL:
```sh
sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt/ xenial-pgdg main" > /etc/apt/sources.list.d/pgdg.list'
wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -
sudo apt-get update
sudo apt-get install postgresql-common
sudo apt-get install postgresql-9.5 libpq-dev
```

Configurando usuário para PostgreSQL (Substitua `usuario` no comando abaixo pelo nome do usuario que você deseja criar):
```sh
sudo -u postgres createuser usuario
```

instalando o node.js:
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.2/install.sh | bash
source ~/.bashrc
nvm install 4.4.7
```

Criando primeiro projeto Rails:
```sh
mkdir rails
cd rails
rails new app
cd app
```

Rodando o projeto Rails:
```sh
bundle exec rails db:crate
bundle exec rails db:migrate
rails s
```

Abra seu browser e vá para o endereço `localhost:3000`

## Código do projeto final no Github
o projeto final que criaremos durante todo o curso está disponível no link abaixo:
https://github.com/PablUoo/EasyContactysGlobal
