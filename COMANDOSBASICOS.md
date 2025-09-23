# 📌 COMANDOS BÁSICOS DO GIT 📌
Ao longo dos últimos três anos, tive a oportunidade de trabalhar em três empresas e aprender diversos comandos e práticas essenciais. Também recebi ensinamentos valiosos de familiares e colegas de trabalho, que me motivaram a estar sempre em busca de novos aprendizados. Hoje, quero compartilhar esse conhecimento com vocês, para que possamos crescer juntos e continuar evoluindo.

---

# 👤 CONFIGURAÇÃO DE USUÁRIO E INTERFACE GUI 👤
- ✅ **Para configurar o usuário de inicio GLOBALMENTE:** git config --global user.name "USER-NAME"
Você Adiciona um Usuário Globalmente para Configurar Diretórios e Servidores Remotos GitHub
- ✅ **Para configurar o email de inicio GLOBALMENTE:** git config --global user.email "USER-EMAIL"
Você Adiciona um Email para o Usuário Globalmente para Configurar Diretórios e Servidores Remotos GitHub
- ✅ **Para configurar o usuário de inicio LOCALMENTE:** git config --local user.name "USER-NAME"
Você Adiciona um Usuário Local de um Único Diretório e Servidor Remoto, sem Editar outros Diretórios ou Servidor Remoto
- ✅ **Para configurar o email de inicio LOCALMENTE:** git config --local user.email "USER-EMAIL"
Você Adiciona um Email Local de um Único Diretório e Servidor Remoto, sem Editar outros Diretórios ou Servidor Remoto
- ✅ **Para listar o usuário de inicio, tanto GLOBALMENTE OU LOCALMENTE:** git config --list
Você Consegue Visualizar Dados do Usuário, Usando este Comando Simples
- ✅ **Para listar aquela tag especifica:** git commit <tag_specifies>
Você visualiza apenas aquela tag que você queira
- ✅ **Para usar outra interface de código:** git config --global core.editor <NAME_GUI>
Você consegue modificar 

--- ⚠️ SEMPRE CONFIGURE SEU USUÁRIO PRIMEIRO, ANTES DE CRIAR UM REPOSITÓRIO LOCAL OU REMOTO ⚠️

# 📁 CRIANDO REPOSITÓRIO LOCAL 📁
- ✅ **Para inicializar um repósitorio local Git:** git init
Você Inicializa dentro do Diretório o git, para usar comandos git dentro dele
- ✅ **Para mudar o nome da Branch Principal:** git config --global init.defaultBranch <NAME_BRANCH>
Você Muda o Nome da sua Branch Principal, Usando Diferentes Nomes Para seu Caminho Principal
- ✅ **Para remover a inicialização do Git no Repositório:** rm -fr .git/
Você remove o git no seu Repositório Local

---

# 🔄 ADICIONANDO MUDANÇAS 🔄
- ✅ **Para visualizar arquivos:** git status
Você Visualiza Arquivos Não Visiveis Dentro do Seu Diretório Local
- ✅ **Para o arquivo ser visivel pro Git:** git add <NAME_ARCHIVE>
Você Adiciona um Arquivo Dentro do Git, Onde vai ser Visivel para ele
- ✅ **Para adicionar todos arquivos a ser visivel pro Git:** git add .
Você Adiciona Todos os Arquivos, Sendo Possível o Git Visualizar Todos Eles

---

# ❌ REMOVER ARQUIVOS ADICIONADOS ❌
- ✅ **Para remover um arquivo visivel do Git:** git rm --cached <NAME_ARCHIVE>
Você Remove Apenas um Arquivo Visivel no Git
- ✅ **Para remover todos arquivos visiveis do Git:** git rm --cached -r .
Você Remove Todos os Arquivos Visiveis no Git

---

# 🌐 SALVANDO MUDANÇAS 🌐
- ✅ **Para salvar mudanças de um arquivo sendo uma commit:** git commit -m "NAME_COMMIT"
Você Cria um Salvamento de Versão Onde Você Consegue Entrar e Conseguir Visualizar Essa Versão a Vontade
- ✅ **Caso queira abreviar o arquivo adicionado e o salvamento da commit:** git commit -a -m "NAME_COMMIT"
Você Passa Automaticamente da Etapa de Adicionar um Arquivo a Ser Visivel e Salvar Commitando Ele

---

# 📂 VISUALIZANDO ARQUIVOS 📂
- ✅ **Para visualizar alterações de arquivos não rastreavel:** git diff
Você Visualiza Alterações que Foram Feitas no Arquivo não Rastreavel Pelo Git
- ✅ **Para visualizar alterações de arquivos rastreaveis:** git diff --staged ou --cached
Você Visualiza Alterações de Arquivos Rastreaveis Pelo Git

---

# 🗂️ HISTÓRICO DE COMMITS 🗂️
- ✅ **Para visualizar commits antigas e que você está utilizando:** git log
Você Visualiza Commits Antigas ou Versões Antigas e Observa Quem Salvou Aquela Commit

---

# 🗂️ HISTÓRICO DE COMMITS - VARIAÇÕES 🗂️
- ✅ **Para visualizar commits de uma forma mais resumida:** git log --oneline
Você Visualiza Commits de uma Forma Mais Resumida, Onde Tem a Hash da Commit e o Nome
- ✅ **Para visualizar commits junto com pacotes:** git log -p
Você Visualiza Commits com Pacotes, Igual a Atualizações de Aplicativos
- ✅ **Para visualizar commits com poucos detalhes:** git log --stat
Você Visualiza as Commits com Alguns Detalhes que Pode Ajudar Você em Algumas Coisas

---

# 🔍 ALTERANDO UM COMMIT 🔍
- ✅ **Para mudar o nome da commit:** git commit --amend -m "NAME_COMMIT"
Você Muda o Nome da Commit, Mas a Hash Dela Acaba Mudando
- ✅ **Para adicionar um arquivo de preparação sem precisar outra commit:** git commit --amend --no-edit
Você Cria Deixa Arquivos Novos ou Modificados na Mesma Commit, Sem Precisar Ficar Muitas Commits
- ✅ **Para editar alguma coisa naquela commit:** git commit --amend
Você Edita sua Commit, Através da Linha de Comando que Está Usando

---

# 📄 USANDO COMMITS ANTERIORES 📄
- ✅ **Para usar uma commit antiga:** git checkout <NAME_COMMIT>
Você Automaticamente usa uma Versão Anterior
- ✅ **Para voltar a usar a commit principal:** git checkout <MAIN/MASTER>
Você Volta Para a Versão Atual

---

# ⏪ DESFAZENDO MUDANÇAS ⏪
- ✅ **Para voltar uma versão anterior do arquivo não commitado:** git checkout <NAME_ARCHIEVE>
Você Volta a Modificações Anteriores, Apenas o Arquivo Modificado
- ✅ **Para deletar arquivos que não estão rastreados:** git clean -f
Você Limpa Arquivos Desnecessários, Caso Não Queira Rastrear
- ✅ **Para voltar a versão anterior dos arquivos não commitados:** git checkout .
Você Volta a Modificações Anteriores de Todos os Arquivos, Sendo Modificado
- ✅ **Para excluir arquivos na zona de preparação quando já tem commits:** git restore --staged <NAME_ARCHIVE>
Você tem Outra Forma de Excluir Arquivos na Zona de Preparação, Mas só Quando Tem Commits no seu Repositório Local
- ✅ **Caso seja para ambos serem excluidos, entre arquivos não rastreados e arquivos rastreados:** git reset --hard
Você Exclui Todos os Arquivos Existentes no seu Repositório, Entre Não Rastreáveis e Rastreáveis

---

# 🚫 IGNORANDO ARQUIVOS 🚫 ----> RECOMENDO PESQUISAREM MAIS SOBRE OS COMANDOS DENTRO DELE
- ✅ **Para ignorar arquivos no Git:** touch .gitignore
Você cria um arquivo gitignore e pode usar ele para ignorar arquivos não interessantes
- ✅ **Para tirar o rastreamento do arquivo quando ele está salvo no git:** git update-index --skip-worktree <NAME_ARCHIVE>
Você Tira o Rastreamento do Arquivo que já Está Commitado no Git, Basicamente Excluido Este Arquivo

---

# ↩️ CLONANDO REPOSITÓRIO ↩️
- ✅ **Para clonar repositórios locais:** git clone <NAME_ARCHIVE_OLD> <NAME_ARCHIVE_NEW>
Você Clona Repositório Local, Sem Precisar se Preocupar com Arquivos Locais
- ✅ **Para clonar repositórios remotos:** git clone <LINK_REPOSITORY>
Você Clona Repositório Remoto, Sem Precisar se Preocupar com Arquivos Remotos