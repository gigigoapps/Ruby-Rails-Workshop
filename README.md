Ruby & Rails Workshop
=====================

Requisitos para asistir al taller:


Instalar Git (si no se tiene ya):

$ \curl -sSL https://get-git.rvm.io | sudo bash


Instalar un gestor de versiones de Ruby (elegir solo uno):


rbenv:

Instalar rbenv: $ git clone https://github.com/sstephenson/rbenv.git ~/.rbenv

Añadir rbenv al $PATH:

Mac: $ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bash_profile

Ubuntu: $ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc

Zsh: $ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.zshrc

Añadir rbenv al autocompletado:

Mac: $ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile

Ubuntu: $ echo 'eval "$(rbenv init -)"' >> ~/.bashrc

Zsh: $ echo 'eval "$(rbenv init -)"' >> ~/.zshrc

Cerrar el terminal para reiniciar la shell y probar que se ha instalado correctamente: $ type rbenv

Instalar ruby-build: $ git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build


NOTA: Si se usa Mac, se puede instalar a través de Homebrew:

Instalar Homebrew (si no se tiene ya): $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Actualizar Homebrew: $ brew update

Instalar rbenv: $ brew install rbenv ruby-build

Añadir rbenv al autocompletado: $ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile


Ver versiones de Ruby: $ rbenv install -l

Instalar una versión de Ruby: $ rbenv install 2.0.0-p247

Usar una versión de Ruby por defecto: $ rbenv global 2.0.0-p247

Recargar configuración de la shell: $ rbenv rehash

Probar versión de Ruby: $ ruby -v

Probar que se está usando rbenv: $ which ruby


RVM:

Instalar RVM: $ \curl -sSL https://get.rvm.io | bash -s stable --rails

Recargar configuración de la shell: $ source ~/.rvm/scripts/rvm

Probar que se ha instalado correctamente: $ type rvm | head -n 1

Ver versiones de Ruby: $ rvm list known

Instalar una versión de Ruby: $ rvm install 2.1.1

Usar una versión de Ruby por defecto: $ rvm use 2.1.1 --default

Probar versión de Ruby: $ ruby -v

Probar que se está usando RVM: $ which ruby


RailsInstaller:

http://railsinstaller.org


Instalar PostgreSQL (si no se tiene ya):

http://www.postgresql.org/download/


Crearse una cuenta en Heroku (si no se tiene ya):

https://id.heroku.com/signup

Instalar Heroku Toolbelt (si no se tiene ya):

https://toolbelt.heroku.com


Instalar las gemas que se van a usar:

$ gem install json

$ gem install pg

$ gem install unicorn

$ gem install sinatra

$ gem install rails

$ gem install devise

$ gem install twitter-bootstrap-rails
