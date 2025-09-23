# 📌 GITHUB 📌
Nesses três anos, li diversos livros e assisti a muitos vídeos no YouTube sobre GitHub, buscando entender como cada recurso funciona e sempre praticando no meu tempo livre. Recentemente, reiniciei meu GitHub para organizar tudo o que aprendi ao longo desse período e compartilhar esse conhecimento com você que está visitando meu perfil.

---

# 🗂️ ENDEREÇO DE REPOSITÓRIO: 🗂️
- ✅ **Para colocar um endereçamento no repositório:** git remote add <name_origin> <link_repository>
Você Coloca um Endereçamento de Inicio no Seu Repositório, Para Ele ser Remoto
- ✅ **Para mudar o endereçamento daquele repositório pra outro:** git remote set-url <name_origin> <link_repository>
Você Muda o Endereçamento Daquele Respositório Quando Criado

---

# 📂 SALVANDO MUDANÇAS NO SERVIDOR: 📂
- ✅ **Para salvar mudanças no servidor, ser colocado no Repositório Remoto:** git push
Você Pega Tudo que Está Dentro do Repositório Pronto e Ataca Tudo no GitHub
- ✅ **Para atualizar a página do Git, quando atualizo lá no GitHub:** git pull
Você Atualiza Tudo Que Está Dentro do Git Quando Algum Colega de Trabalho Fez Alguma Modificação no Repositório Remoto

---

# 🔐 CHAVE SSH: 🔐 ----> RECOMENDO LER A DOCUMENTAÇÃO OU VER VÍDEOS, PARA ENTENDER MELHOR ESSE MÉTODO DE ENTRADA
- ✅ **Para criar uma chave ssh na máquina local:** ssh-keygen
Você Cria uma Chave SSH na Sua Máquina Local, Conseguindo Acessar Essa Chave
- ✅ **Para iniciar uma chave ssh, para o git entender:** eval $(ssh-agent)
Você Inicia um Agente, Onde o Git Vai Entender Que Você Está Iniciando Uma Chave no Seu Repositório Local
- ✅ **Para adcionar uma chave ssh, que o git entenda:** ssh-add ~/.ssh/<name_ssh>
Você Adiciona Uma Chave SSH, Onde Você Vai Clonar o Seu Repositório Remoto