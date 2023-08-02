# Exemplos de operações básicas para via CLI

## Comandos de Uso geral da CLI

- Criar pasta: mkdir nomepasta
- Listar conteúdo: dir
- Limpar tela: cls
- Entrar na pasta: cd nomepasta

## Comandos principais do git
`git config user.name` e `git config user.email`

Verificar usuário/email


`git config --global user.name "Seu nome como quiser"` e `git config --global user.email "seuemail@provedor.com"`

Mudar usuário e e-mail de forma global

**Obs:** normalmente estes dados estão relacionados ao usuário/conta do site GitHub.

`git init`

Inicializar um repositório (executado dentro da pasta)

`git branch nome-branch-atual novo-nome-para-branch`

Renomear branches
Renomear a branch de **master** para **main** (novo padrão),Usaríamos: `git branch master main`



`git status`

Verificar o status atual do repositório

`git add nomearquivo`

Adicionar (tornar arquivo rastreável) ao monitoramento do git.

`git commit -m "Texto da mensagem sobre esta alteração"`

Fazer commit das alterações (salvar no histórico).

`git remove add origin endereço-do-repositorio.git`

Adicionar/conectar o repositório remoto ao local.

`git clone endereço-do-repositório.git`

Copiando/baixando um repositório para a máquina remota.

`git push origin main`

Enviar as mudanças para o GitHub (PUSH)

`git pull origin main`

Pegar/obter as mudanças do repositório online GitHub (PULL)