# Projeto base para ensino das tecnologias Ruby + React.

Este projeto será utilizado para ensino, vou criar os passos para instalar o Ruby, Npm e PostgreSQL.

Projeto baseado no post: (https://medium.com/@bruno_boehm/reactjs-ruby-on-rails-api-heroku-app-2645c93f0814)

# Instruções:

* Ruby version
- Eu uso o rbenv para instalar o ruby e suas versões, seguem mais detalhes (https://www.ruby-lang.org/pt/documentation/installation/)

* System dependencies
- NPM https://www.npmjs.com/get-npm

* Configuration
- depois que colocar o axios no package, rodar yarn install

* Database install: PostgreSQL
- (https://www.postgresql.org/download/)

* Database initialization
- rake db:create
- rake db:migrate (sempre que tiver migrate nova, vamos rodar este comando)

* How to run the test suite: Rspec

* Services: Rails e React
- rails s -p 3001
- yarn start

# React com Yarn (https://yarnpkg.com/pt-BR/)
  - yarn start
    Starts the development server.

  - yarn build
    Bundles the app into static files for production.

  - yarn test
    Starts the test runner.

  - yarn eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

  - We suggest that you begin by typing:
    cd client
    yarn start

