Instalar Git

$ sudo apt-get install git

- Verificar versão:

$ git --version

- Criar um site estático

- Configurar o nome de usuário do GitHub:

$ git config --global user.name "nome"

- Configurar o email de usuário do GitHub:

$ git config --global user.email "email@email.com"

- Criar uma conta no GiHub

- Criar um repositório para hospedar o site estático no GitHub:

Nome do repositório:	

	nome-da-conta.github.io

Exemplo:

	armitage256.github.io


Executar os comandos:

// Inicializa o repositório
git init

// Adiciona todos os arquivos e pastas
git add .

// commit
git commit -m "first commit"

git remote add origin https://github.com/armitage256/armitage256.github.io.git

git push -u origin master


END
/

