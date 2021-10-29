### Resumo do Conteúdo do Curso

- Comandos  básicos de navegação no terminal

  **Windows**  	 	**Linux**			**Descrição** 

  cd						cd			 	Mostra o conteúdo da pasta

  dir					   ls			   	listar o conteúdo da pasta		

  mkdir				 mkdir			Criar uma pasta

  del / rmdir		rm rf		  	Apagar uma pasta - 'del' para arquivos e 'rmdir' para repositórios.

  cd /					 cd /			    Navegar para um local específico no sistema

  cd ..					cd ..		   	 Retrocede 1 nível

  cls			   clear / CTRL+L	 Navegar para um local específico no sistema

  tab 											autocompletar 

  

- Primeiros comandos com Git - Criando um repositório

  1. Criar a pasta (repositório) no computador

  2. Abrir o Git Bash dentro da pasta   

  3. Dar o comando git init - Iniciar um repositório no Git desta pasta

  4. git config --global user.name "nome"

     git config --global user.email "email@email.com"

  5. Criar os arquivos que desejar dentro dessa pasta

  6. git add * - move todos os arquivos novos ou modificados para "staged"

  7. git commit -m "mensagem de descrição do commit" - Fazer o commit

  8. git push origin main - Empurrar o arquivo para o repositório remoto.

  

- Movendo para o GitHub - PUSH

  1. Dentro do GitHub criar um repositório com o mesmo nome da pasta criada anteriormente.

  2. Copiar a URL do repositório

  3. Dentro do Bash da pasta do repositório dar o comando:

     git remote add origin +link copiado

  4. git push origin main(ou master) 



- Alguns comandos Git

  ls - listar o conteúdo

  ls -a - Mostra conteúdo oculto

  git status - para ver o status do repositório

  git config --global -- unset user.email - apaga o email para ser cadastrado novamente

  

- Criando o repositório direto no GitHub e movendo para o computador - PULL

  1. Criar o repositório no GitHub 

  2. Copiar a URL no botão "Code"- CLONE

  3. Dentro da pasta deseja no computador abrir o Git Bash e seguir com o comando:

     git clone +URL copiada 

     

  Em caso de alterações nos arquivos, é necessário sempre seguir passos de add, commit e push para que as alterações sejam publicadas no espaço remoto.

  

  

  

  

