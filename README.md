# Teste para Estagiário de Desenvolvimento PHP

Bem-vindo ao teste para a posição de estagiário de desenvolvimento PHP utilizando o framework Laravel e o banco de dados MySQL. Neste teste, você será conduzido e avaliado em suas habilidades de desenvolvimento web, CRUD de login, recuperação de senha, uso do DataTables e manipulação de planilhas XLS.

## Instruções gerais

- Clone este repositório em sua máquina local antes de começar o teste.
- Crie um novo branch a partir do branch `main` com o seu nome.
- Ao finalizar o teste, faça um commit das suas alterações no seu branch e crie um Pull Request para o branch `main`.
- Certifique-se de que todas as dependências necessárias estão instaladas antes de executar o projeto.
- Consulte a documentação do Laravel para obter informações sobre como lidar com upload de arquivos.

## Requisitos

Antes de começar, verifique se você possui os seguintes requisitos instalados em seu ambiente de desenvolvimento:

- Docker
- Docker Compose

Certifique-se de que o Docker e o Docker Compose estejam devidamente instalados em sua máquina antes de prosseguir.


## Instruções gerais

- Clone este repositório em sua máquina local:
```git clone https://github.com/dhell-net/laravel-starter.git```
- Acesse o diretório do projeto:
```cd laravel-starter```
- Execute o seguinte comando para iniciar o ambiente de desenvolvimento:
```./vendor/bin/sail up```

Isso iniciará os contêineres Docker necessários para a aplicação Laravel.

- Após iniciar o ambiente, acesse a aplicação em seu navegador através do seguinte endereço:
```http://localhost```


## Desafio 1: CRUD de Login e Recuperação de Senha

Seu primeiro desafio é implementar um sistema de login com funcionalidade de recuperação de senha utilizando o Laravel. O sistema deve permitir que os usuários se registrem, façam login, solicitem a recuperação de senha e redefinam suas senhas.

Requisitos:
- Implemente as rotas, controladores, modelos e visualizações necessárias para o CRUD de login.
- Os usuários devem poder se registrar, fazer login, solicitar a recuperação de senha e redefinir suas senhas.
- Utilize as funcionalidades de autenticação e recuperação de senha fornecidas pelo Laravel.

Dicas:
- Consulte a documentação do Laravel para obter informações sobre como implementar autenticação e recuperação de senha.
- Utilize as migrations do Laravel para criar a estrutura do banco de dados necessária para o sistema de login.

## Desafio 2: Visualização de Lista de Arquivos utilizando DataTables

Seu segundo desafio é implementar a visualização de uma lista de arquivos enviados utilizando a biblioteca DataTables. Os arquivos devem ser exibidos em uma tabela com recursos de paginação, pesquisa e ordenação.

Requisitos:
- Crie uma rota `/arquivos` que exiba a lista de arquivos enviados.
- Utilize a biblioteca DataTables para exibir a tabela com os arquivos.
- Implemente recursos de paginação, pesquisa e ordenação na tabela.

Dicas:
- Consulte a documentação do DataTables para obter informações sobre como utilizá-lo com o Laravel.
- Utilize o Eloquent ORM do Laravel para recuperar os dados dos arquivos do banco de dados.

## Desafio 3: Upload de Planilhas

Seu terceiro desafio é implementar um recurso de upload de planilhas XLS usando o Laravel. O usuário deve poder fazer o upload de um arquivo XLS através de um formulário. O arquivo deve ser salvo no servidor e os dados contidos na planilha devem ser armazenados no banco de dados MySQL.

Requisitos:
- Crie uma rota `/upload` que exiba um formulário para o usuário fazer o upload da planilha.
- Valide o arquivo enviado para garantir que seja um arquivo XLS válido.
- Armazene os dados da planilha no banco de dados utilizando as melhores práticas do Laravel.
- Exiba uma mensagem de sucesso após o upload da planilha.

Dicas:
- Consulte a documentação do Laravel para obter informações sobre como lidar com upload de arquivos.
- Utilize a biblioteca PHPExcel ou similar para ler os dados da planilha XLS.

## Considerações finais

- Sinta-se à vontade para adicionar qualquer funcionalidade extra que considere relevante.
- Documente quaisquer instruções adicionais ou considerações no README.md do projeto.
- Ao finalizar o teste, faça um commit das suas alterações e crie um Pull Request.

Boa sorte! Se tiver alguma dúvida, não hesite em entrar em contato por email(ti@dhell.net) ou pelo whatsapp.
Estamos ansiosos para ver a sua evolução!
