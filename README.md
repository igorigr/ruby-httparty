# Projeto Base Automação API - Ruby, httparty & Cucumber(BDD) + Rspec

![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-43B02A?style=for-the-badge&logo=cucumber&logoColor=white)




## Ferramentas utilizadas:
- [Ruby](https://www.ruby-lang.org/en/ "Ruby")
- [httparty](https://rubygems.org/gems/httparty "httparty")
- [Cucumber](https://cucumber.io/ "Cucumber")
- [Rspec](https://rspec.info/ "Rspec")

## DEPENDENCIES

  httparty
  cucumber
  json
  rspec

## Pré-Requisitos para utilização:

- Possuir uma versão do Ruby instalado. (Required ruby-3.2.2 )
- Mapear o arquivo Gemfile na pasta principal.
- Instalar as bibliotecas necessárias para funcionamento do Httpparty, para
isso basta abrir o terminal na pasta do projeto e executar os comandos a seguir:

- Install the gem:

bundle

- Install the httparty:

gem install httparty

- Install the Cucumber:

gem install cucumber

- Then, initialize a features/ directory:

cucumber --init

- Install the rspec:

gem install rspec

- Install the multi_xml

gem install multi_xml

Referências:

- [Cucumber para Ruby](https://cucumber.io/docs/installation/ruby/ "Cucumber")


### Arquitetura - Bibliotecas utilizadas

Neste projeto foi utilizada a linguagem Ruby com a Gem httparty, para fazer a automação em testes de APIs e a Gem Rspec para fazer as validações e o Cucumber para escrever as features BDD.

```
├── README.md
├── .idea
    └── gitignore
    └── CucumberTeste.iml
    └── modules.xml
    └── workspace.xml
    └── features
        └── specifications
            ├── TipoEstabelecimentoVr.Feature
        ├── step_definitions
            └── TipoEstabelecimentoVr_steps.rb
└── .ruby-version
├── Gemfile
├── Gemfile.lock

```

### Sobre o Projeto

Neste projeto foi utilizada uma API da VR, onde os requisitos são:

- Efetuar uma request na API buscando todos os tipos de estabelecimentos
- A resposta será um Json que retorna uma série de informações sobre produtos e estabelecimentos.
- Validar que o JSON retornado pelo serviço possui a chave “typeOfEstablishment” e print, aleatoriamente, um desses tipos de estabelecimentos.


### Como executar o Projeto

No terminal executar o seguinte comando do cucumber

- Para rodar o Teste Todo

cucumber 

- Para rodar o Teste Unitario por Cenário de acordo com a Tag

cucumber --@NomeDaTag
