# TrabalhoPratico1-Cypress
Repositório do Trabalho Prático 1, da matéria S206-L1, sobre Teste de UI com Cypress

Nome: Willy Paim Ribeiro de Paula

Curso: Engenharia de Software (GES)

Matrícula: 93

Site utilizado para os testes: https://www.imdb.com/

Testes realizados no site:

1 - Inserindo as informações para cadastro no site de forma correta, sem a resolução do captcha.

2 - Inserindo as informações para o cadastro utilizando um email já cadastrado, gerando um erro no cadastro.

3 - Inserindo as informações para o cadastro utilizando uma senha diferente no campo de confirme a sua senha, gerando um erro no cadastro.

4 - Busca de uma título no site, retornando qualquer obra que possua esse título em seu nome, podendo ser filme, série, documentário, entre outros.

5 - Verificando se na aba de vencedores do oscar o título vencedor está com um emblema de vencedor, para isso foi necessário utilizar os menus do site.

6 - Buscando apenas filmes com o gênero ação, para isso foi necessário ir na aba de buscar filmes por gênero e selecionar a opção do gênero ação.


Execução do Projeto:

1 - Realizar a cópia do repositório para máquina pessoal.

2 - Instalar as dependências do Cypress na máquina utilizando os comandos:

    npm init
    
    npm install cypress

3 - Baixar as dependencias do projeto:

    npm install

4 - Executar o projeto:

    Utilizando o Cypress: ./node_modules/.bin/cypress open

    Utilizando o Terminal: ./node_modules/.bin/cypress run --spec 'cypress/e2e/**/'


Gerar o Relatório de Testes:
1 - Adicionar as dependências do mochawesome:

    npm i --save-dev cypress-mochawesome-reporter

2 - Executar o projeto:

    ./node_modules/.bin/cypress run --spec 'cypress/e2e/**/'
