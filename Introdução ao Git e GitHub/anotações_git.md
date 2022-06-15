# Git e GitHub

### Git: Sistema de Controle de Versões Distribuído
- Linus Trovalds
- Kernel Linux

### Git Bash: Command Line Interface (CLI)
- Comandos Básicos:
	+ cd (chance directory): mudar de diretório
	+ ls (list): listar arquivos e diretórios
	+ mkdir (make directory): criar diretório
	+ rm -rf (remove recursively and forcibly): remove arquivos e diretórios

### Segurança
- SHA1 (Secure Hash Algorithm): Funções Hash Criptográficas. Identificador único de 40 caracteres.
- Versões disponíveis nos diretórios locais são confiáveis.

### Objetos do Git
- Blobs: Estrutura básica que contém o arquivo
	+ Metadados: tipo do objeto, tamanho da string e conteúdo
- Trees: Armazenam e apontam para as Blobs, outras Trees e commits.
	+ Metadados: nome e SHA1 das blobs, tipo e tamanho
- Commits: Aponta para outros commits, trees e autores
	+ Metadados: tree, commit parente, autor, mensagem e timestamp

### Comandos Git
- git init: inicia o Git no diretório
- git add: move o arquivo para a área de staging e o marca para realizar o commit
- git commit: gera o commit (snapshot do repositório)
- git status: mostra a situação atual dos arquivos
- git push: faz o upload do repositório local para o repositório remoto
- git pull: atualiza o repositório local conforme o repositório remoto
- git clone: cria uma cópia de determinado repositório

### Configuração Inicial
- git config --global user.email "{*email}"
- git config --global user.name "{name}"

### Markdown: Linguagem de marcação
- Simplifica e padroniza a formatação de texto na web
- Utilizado nos arquivos README