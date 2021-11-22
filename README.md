# 4linux-521

Python for API

## Conteúdo do curso

# dia 1: review python + requests ( como enviar/consumir endpoints) |
  Contexto web | Protocolo HTTP ( quem consome)

# dia 2: Flask ( quem serve)
    comandos
    instala
    funcionamento interno
    como criar endpoints e apis
    templates -> Jinja2
                macros, modulos
    blueprint
    projetos
    api integra com o mongodb

# dia 3: container
        Docker
        container x vms
        Docker CLI
        executar containeres
        criar imagens
        criar redes
        uso de variáveis de ambiente
        docker-cmpose
        container a aplicação

# dia 4/5: Autenticacação e autorização
        Cookie
        Session
        Flask <> Sessions
        Stateful x Stateless
        Tokens JWT
        Implementa autenticação / autorização
    
# dia 5: Logs
        modulos logging
        criar arquivo de configuração de log
        json

# dia 6: Projeto: Serviços
        # Ambiente de desenvolvimento moderno
        > Versionamento de código <> Git + Gitlab-CI (runners)
        > Integração contínua ( automação) Pipelines Testes
        > Verionamento de artefato > Imagem de container (registry) Dockerhub
        > Deploy -> homolog/staging > Heroku (Dyno)

# dia 7: Versionamento de código com git + gitlab
        > O que é git / como funciona / sua estrurura de dados
        > principais usos
            >> Modelosde projetos (GitFlow | Trunk Based)
        > gitlab como gerenciador de repositórios do git
            >> Issue Oriented Flow

# dia 8: CI com Gitlab
        > Contruir pipelines
        > como automatizar testes
        > como integrar o gitlab com o dockerhub
        > gerenciamento de credenciais e usos de variáveis de ambiente
        > prévia desse versionamento de artefatos

# dia 9: Heroku
        CLI do heroku
        publicação de um app no heroku
        uso de imagens de contianer no heroku
        integrar o heroku na pipeline do gitlab

# dia 10: Projeto
        simular um teste técnico
        focado em dev backend
        api que consome um banco de dados
        + utilizarem tecnologias de container
        + demonstrarem conhecimento de etapas de CI

