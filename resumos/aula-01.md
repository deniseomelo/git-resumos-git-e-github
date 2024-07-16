# Git e GitHub: Ferramentas Essenciais para o Desenvolvimento de Software

Git e GitHub são duas ferramentas fundamentais no mundo do desenvolvimento de software, proporcionando controle de versão e colaboração eficiente entre desenvolvedores.

## Git

Git é um sistema de controle de versão distribuído criado por Linus Torvalds em 2005. Ele permite que desenvolvedores rastreiem mudanças no código-fonte ao longo do tempo, revertam para versões anteriores, e trabalhem simultaneamente em diferentes partes de um projeto sem conflitos. Aqui estão alguns conceitos-chave do Git:

- **Repositório (Repo)**: Um repositório é um local onde o histórico de versões de um projeto é armazenado. Ele pode ser local (no computador do desenvolvedor) ou remoto (em um servidor).

- **Commit**: Um commit é uma captura do estado atual do projeto. Cada commit tem uma mensagem descritiva e um identificador único (hash), permitindo rastrear as mudanças específicas feitas no código.

- **Branch**: As branches (ramificações) permitem que desenvolvedores trabalhem em funcionalidades ou correções de bugs separadamente do código principal. A branch principal é geralmente chamada de "main" ou "master".

- **Merge**: Merging (mesclagem) é o processo de integrar mudanças de uma branch de volta à branch principal ou a outra branch. Isso ajuda a consolidar o trabalho de diferentes desenvolvedores.

- **Pull e Push**: "Pull" é a ação de trazer mudanças do repositório remoto para o repositório local. "Push" é o envio de mudanças do repositório local para o repositório remoto.

## GitHub

GitHub é uma plataforma baseada na web que hospeda repositórios Git, oferecendo ferramentas adicionais para colaboração e gerenciamento de projetos. Algumas das principais funcionalidades do GitHub incluem:

- **Repositórios Remotos**: GitHub permite que os repositórios Git sejam armazenados na nuvem, facilitando o acesso e a colaboração entre desenvolvedores de qualquer lugar do mundo.

- **Forks**: Um fork é uma cópia de um repositório que permite ao desenvolvedor fazer mudanças sem afetar o repositório original. Isso é útil para colaborar em projetos de código aberto.

- **Pull Requests**: Um pull request é uma solicitação para mesclar mudanças de um fork ou de uma branch para a branch principal do repositório. Ele permite revisão de código e discussão antes que as mudanças sejam integradas.

- **Issues e Project Boards**: Issues (questões) são usadas para rastrear tarefas, bugs e melhorias no projeto. Os project boards (quadros de projeto) ajudam a organizar e planejar o trabalho, semelhante a um quadro Kanban.

- **Actions**: GitHub Actions permite automatizar fluxos de trabalho, como testes de integração contínua e entrega contínua (CI/CD), tornando o processo de desenvolvimento mais eficiente.

## Principais Comandos do Git

### Comandos Básicos

1. **Configuração Inicial**
   ```sh
   git config --global user.name "Seu Nome"
   git config --global user.email "seuemail@example.com"

2. **Criação e inicialização de Repositório**
   ```sh
   git init
   git clone [URL do repositório]

3. **Comandos de Status e Histórico**
   ```sh 
   git Status
   git log
   git diff

4. **Adicionando e Confirmando Alterações**
   ```sh
   git add [arquivo]
   git add .
   git commit -m "mensagem do commit"

5. **Trabalhando com branches**
   ```sh
    git branch
    git branch [nome-da-branch]
    git checkout [nome-da-branch]
    git merge [nome-da-branch]

6. **Atualizando e Enviando Alterações**
   ```sh
   git pull
   git Push
   git push -u origin [nome-da-branch] 

7. **Revertendo Alterações**
   ```sh
   git reset --hard [commit]
   git revert [commit]

### Comandos Avançados 

1. **Stashing**
   ```sh
   git stash
   git stash apply
   git stash drop

2. **Rebase**  
   ```sh
   git rebase [branch]
   git rebase --interactive [commit]

3. **Tags**
   ```sh
   git tag [nome-da-tag]
   git push origin [nome-da-tag]

4. **Log Avançado**
     ```sh
     git log --oneline --graph --decorate --all
5. **Submódulos**
   ```sh
   git submodule add [URL do repositório] [caminho]
   git submodule update --init --recursive
   
   ```
