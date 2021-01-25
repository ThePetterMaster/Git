# GIT E GITHUB

Guia prático para iniciantes.

### Instalação

https://git-scm.com/download

# SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto
- [x] Você deseja verificar mudanças feitas no seu projeto

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

- [x] Você quer colocar seu projeto na nuvem.

- [x] Você vai pegar um projeto já iniciado, para trabalhar com o time
- [x] Você precisa resolver um conflito.
- [x] Antes de enviar a resolução, precisamos atualizar o projeto local.

- [x] Você precisa voltar um arquivo para um determinado momento da linha do tempo.
- [x] Você precisa recuperar algo deletado.

* `git init` // inicia a linha do tempo
* `git add nomearquivo.extensao` ou só `git add .` para todos os arquivos no diretório// adiciona ou atualiza mudanças para irem para a linha do tempoo
* `git commit -m "Mensagem descrevendo a mudança"` // adiciona um ponto na linha do tempo
* `git log` // visualiza os pontos na linha do tempo / vizualiza todos os commit
* `git status` // informa o estado das alterações do nosso projeto
* `git show`para a ultima alteração ou `git show numerodocomitespecifico` // mostra o que foi alterado
* `git branch nomedalinhadotempo` para criar uma linha do tempo ou `git branch nomedalinhadotempo -D` para deletar essa linha do tempo// gerenciar novas linhas do tempo
* `git checkout nomedabranch` // manipula as linhas do tempo
* `git merge nomedabranch` // unir a linha do tempo com a especificada
* `git remote add origin urlDoRepositorioNoGitHub` // Conectar ao repositório do github
* `git push` // envia alterações locais para o repositório remoto
* `git clone urlDoreponogithub` // clonar um projeto / repositório
* `git pull` // puxa do repositório remoto
