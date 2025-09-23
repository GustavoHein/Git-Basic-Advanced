# 📌 BRANCHES 📌
No início da minha carreira, tive bastante dificuldade para trabalhar com branches. Com o tempo, comecei a criar projetos simples para entender melhor como funcionavam esses caminhos e evitar problemas de ramificação. Muitas vezes surgiam desafios na área em que eu trabalhava, mas segui firme, sempre dando o meu melhor para compreender e dominar o uso de branches.

# 📁 CRIANDO BRANCH LOCAL: 📁
- ✅ **Para criar uma ramificação da branch principal:** git branch <name_branch>
Você Cria Uma Ramificação, Onde Você Pode Testar Códigos, Sem Mexer Na Branch Main
- ✅ **Para entrar dentro dessa branch:** git checkout <name_branch>
Você Entra Dentro da Branch, e Consegue Fazer ou Editar Commits
- ✅ **Para fazer o trabalho desses dois códigos em um:** git checkout -b <name_branch>
Você Vai Criar a Branch e Entrar Automaticamente Nela
- ✅ **Para alterar em caminhos de branches diferentes:** git switch - ou <name_branch>
Você Navega por Branches Diferentes e Consegue Editar Elas
- ✅ **Para conseguir visualizar as branches:** git branch --list
Você Consegue Visualizar Uma Lista Completa Das Branches Que Você Criou

---

# 🗃️ MUDANÇAS NÃO SALVAS: 🗃️
- ✅ **Para tirar mudanças não salvas de outra branch:** git checkout -f <name_branch>
Você Tira Mudanças Não Salvas de Outras Branches

---

# 🔄 DETACHED HEAD: 🔄
- ✅ **Para configurar uma commit antiga para virar uma branch:** git switch -c <name_branch>
Você Utiliza Uma Commit Antiga e Consegue Editar Ela, Criando Uma Branch, Um Caminho de Ramificação

---

# 🌐 ENVIANDO BRANCH PARA O REPOSITORIO REMOTO: 🌐
- ✅ **Para colocar a branch no GitHub:** git push --set-upstream origin <name_branch> ou git push -u origin <name_branch>
Você Consegue Colocar Branchs No Repositório Remoto, Onde Você Consegue Visualizar ou Editar Depois

---

# ❌ REMOVENDO BRANCH LOCAL: ❌
- ✅ **Para remover uma branch local:** git branch -d <name_branch> ou git branch -D <name_branch>
Você Remove Uma Branch Remota Sem Nenhumma Preocupação
 
---

# ❌ REMOVENDO BRANCH REMOTA: ❌
- ✅ **Para remover uma branch remota:** git push --delete origin <name_branch>
Você Remove a Branch no GitHub e Depois Pode Remover Localmente

---

# 📄 RENOMENANDO BRANCH: 📄
- ✅ **Para renomear a branch dentro dela:** git branch -m <name_branch>
Você Está Dentro da Sua Branch e Pode Mudar o Nome Dela Quando Quiser
- ✅ **Para renomear fora da branch:** git branch -m <name_branch> <new_name_branch>
VocÊ Está Fora da Sua Branch e Consegue Renomear Ela Quando Quiser

---

# 🔍 HISTÓRICO DE ALTERAÇÕES EM DIFERENTES BRANCH: 🔍
- ✅ **Para ver alterações de commits em uma branch:** git log <name_branch>
Você Visualiza Alterações Feitas Durante o Tempo Daquela Branch