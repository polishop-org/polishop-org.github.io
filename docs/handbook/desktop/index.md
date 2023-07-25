# Github Handbook - Utilizando GitHub Desktop

Este Handbook tem o intuito de juntar as principais informações do GitHub Desktop para o dia-a-dia. As funções mais complexas são absorvidas no material completo.

Aqui algumas referências que podem te ajudar!

## Links úteis

### GUIA RÁPIDO -> GIT & GITHUB

### Instalando GitHub Desktop

- [https://desktop.github.com/](https://desktop.github.com/)

---

### Obtenha um repositório

Para clonar um repositório:

1. No GitHub Desktop, clique em "File" -> "Clone Repository".
2. No campo "URL", digite o URL do repositório que deseja clonar.
3. Clique em "Clone".

---

### Adicionando Arquivos:

Para fazer commit de alterações:

1. Faça as alterações nos arquivos na sua pasta local do repositório.
2. No GitHub Desktop, os arquivos alterados serão listados.
3. Adicione um resumo e uma descrição para o commit.
4. Clique em "Commit to main" (se estiver na branch main).

Obs: Git é o sistema de versionamento de arquivos; Github é o repositório online para guardar estes arquivos.
O "commit" no GitHub Desktop garante o versionamento, mas NÃO garante que os arquivos estão no Github.

### Fazendo upload dos arquivos:

1. Depois de fazer um commit, clique em "Push Origin" para enviar os commits para o repositório remoto.

---

### Ramificando (trabalhando com branches):

1. Para criar um novo branch, clique em "Current branch" -> "New branch" e digite o nome da nova branch.
2. Para alternar entre branches, clique em "Current branch" e selecione a branch que deseja.
3. Para deletar uma branch, clique em "Current branch" -> "Delete branch".
4. Para enviar a nova branch para o repositório remoto, clique em "Publish branch".

### Atualizar e mesclar (merge):

1. Para atualizar o seu repositório local para a versão mais recente, clique em "Fetch Origin". Se houver novos commits no repositório remoto, clique em "Pull Origin".
2. Para fazer o merge de uma branch para a branch ativa, vá para a branch que você deseja fazer o merge, clique em "Branch" -> "Merge into Current Branch" e selecione a branch que você deseja mesclar.
3. Se houver conflitos, você terá que resolvê-los manualmente nos arquivos afetados. Depois de resolver os conflitos, faça um commit das alterações.
4. Para visualizar as diferenças entre duas branches, selecione a branch que deseja comparar no menu "Current branch".
