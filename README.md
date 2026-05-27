# primer_repositorio


Eyck, Julio, Lucas, Pedro

- Git - Sistema de controle de versões distribuído
	- 6.1. Evolução
	- 6.2. Comandos iniciais
		- 6.2.1.Init
		- 6.2.2.Add
		- 6.2.3.Status
		- 6.2.4.Config
		- 6.2.5.Commit
		- 6.2.6.Log



- Versionamento em nuvem
	- 7.1. Serviços
		- 7.1.1.Github
		- 7.1.2.BitBucket
		- 7.1.3.Azure Repository

---


# git ~ eyck

git é um **sistema de armezenamento** de versoes de um codigo-fonte  

- principais caracteristicas
  - controle de versões
  - gerencia todos arquivos em uma pasta
  - distribuido
     - permite controle do projeto em diferentes compurtadores atraves de um "clone" do projeto
   

# git init ~ julio

O comando git init normalmente é o primeiro comando utilizado em um projeto Git.
Ele transforma uma pasta comum do computador em um repositório Git, permitindo o controle de versões dos arquivos e a execução dos comandos do Git no diretório.

- principais caracteristicas
  - Geralmente é o primeiro comando utilizado no Git.
  - Transforma uma pasta comum em um repositório Git.
  - Cria uma pasta oculta chamada .git
  - Permite o controle de versões dos arquivos.
  - Habilita a execução dos comandos Git dentro do diretório.

# git add ~ julio
git add é um comando utilizado no git.

O git add prepara as alterações realizadas nos arquivos para serem registradas.

- principais caracteristicas
  - Prepara as alterações dos arquivos.
  - Adiciona os arquivos à área de stage\área de prepapação.
  - Define quais mudanças serão registradas.

# git statusd ~ takeo
gits status é um comando utilizado para verioficar o estado atual do repositorio no git

- principais caracteristicas
  - mostra arquivos modificados
  - arquivos prontos para commit
  - arquivos não rastreados
  - situação da "branch"

- 6 Git - Sistema de controle de versões distribuído
	- 6.1. Evolução
	- 6.2. Comandos iniciais
		- 6.2.1.Init
		- 6.2.2.Add
		- 6.2.3.Status
		- 6.2.4.Config
		- 6.2.5.Commit
		- 6.2.6.Log
- 7 Versionamento em nuvem
	- 7.1. Serviços
		- 7.1.1.Github
		- 7.1.2.BitBucket
		- 7.1.3.Azure Repository
	- 7.2. Pull Requests
	- 7.3. Resolução de conflitos


# Git config 

- Descrição
  - é um comando para ler, definir e alterar configuração no git
  - informanções e preferencias do usuário em 3 niveis diferentes
     - Local (--local): Afeta apenas o repositório atual. (Armazenado em .git/config)
     - Global (--global): Afeta todos os repositórios do seu usuário no sistema. (Armazenado em ~/.gitconfig)
     - Sistema (--system): Afeta todos os usuários e projetos do sistema operacional. (Armazenado em /etc/gitconfig)
- Exemplos
  - Configurar o seu nome:
    - git config --global user.name "Seu Nome"
  
  - Configurar o seu e-mail:
    - git config --global user.email "seu-email@exemplo.com"
  
  - Listar todas as configurações ativas:
    - git config --list    

# Bitbucket 

- Descrição
 - é uma plataforma de hospedagem de codigo-fonte baseado no git
 - Utilidad
 - oferece um ambiente centralizado para equipes de desenvolvimento
 - armazena, revisa e gerencia projetos de software
 - oferece recursos essenciais para o ciclo do desenvolvimentos de software
- funções
  - Gerenciamento de Código
  - Revisão de Código (Pull Requests)
  - Automação de CI/CD (Bitbucket Pipelines
  - Rastreamento de Problemas (Issues)
  - Integração com ecossistema Atlassian
