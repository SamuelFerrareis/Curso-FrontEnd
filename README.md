# Curso-FrontEnd
#### Ebac

# Git
## Versionamento
- Histórico
- Controle de Versão
- Quem Alterou
- O que Alterou
- Quando Alterou
- Todos os Arquivos
- Evolução Continua

Arquivo A | Versão 1 | Versão 2
Arquivo B | Versão 1 | Versão 2

## Instalação do Git

Linux (apt-get): sudo apt-get install git
Mac (Brew): brew install git


## Criar conta do GitHub

## Clonar o projeto
git clone https://github.com/SamuelFerrareis/Curso-FrontEnd.git

## Abrir Repositório
- cd Curso-FrontEnd/

## Commits
Informação de Alteração
- após testado todo seu código
- git add *
- git commit -m "mensagem"
- git push (enviar alterações para o repositorio)
- git pull (puxas / trazer alterações do GitHub para sua máquina)

## GitFlow
fluxo do git

### Branchs
São Ramificações / versão paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop ()
- DOD Definition of Done: Critérios de aceite
- versionamento 1.0.0

git checkout -b dev (cria uma branch)
git checkout master (mudar de branch)


### Merge
Mescla de Branchs
Você pode precisar resolver conflitos manualmente

git merge main 

### Pull Request
Mescla de Branchs no repositorio
Permite Code review
O Repositório resolve os conflitos automaticamente
