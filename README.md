# Vitta-caseQA
Respostas da questẽos propostas

## Cássio Moreira Silva

1. Desenvolva os casos de testes a partir das Stories apresentadas abaixo, descrevendo ao menos um cenário feliz e um cenário alternativo para cada uma das Stories.
  *001**
001 - Como a "pessoa física" gostaria de realizar o cadastro na loja:

Descrição: Realizar cadastro de uma pessoa física na plataforma de vendas web da Saraiva.

Pre-requisitos:
1 - Acesso: https://www.saraiva.com.br
2 - CPF válido.

Cenário de teste
1 - Acessar a página da Saraiva pela URL: https://www.saraiva.com.br e validar que o endereço é válido.
1 - Página carregada com sucesso, com as corres amarelo e preto.

2 - Clicar sobre o componente "Entre ou cadastre-se" no canto superior direito da página e validar que uma nova página é aberta.
2 - Nova página de login acessada com sucesso, com as cores amarelo e preto.

3 - Acessar o modal e, clicar sobre o conponete de "Entrar com Cliente Saraiva ou Cadastre-se", validar que uma nova página é aberta.
3 - Nova página de cadastro acessada com sucesso, com as corres amarelo e preto.

4 - Clicar sobre o botão de "Cadastrar" e validar que uma nova página é aberta para cadastro.
4 - Nova página de cadastro acessada com sucesso, com as corres amarelo e preto.
5 - Selecionar "Pessoa Física" na opção de pessoa PF ou PJ.
5 -  Validado com sucesso, campos exibidos de pessoa PF.


6 - No campo de "Nome" preencher com nome válido ou com mais de 2 caracteres, sem números ou caracteres especias.
6 - Preenchido com sucesso.

7 - No campo de "Sobrenome" preencher com sobrenome válido ou com mais de 2 caracteres, sem números ou caracteres especias.
7 - Preenchido com sucesso.

8 - No campo de "E-mail" inserir um e-mail válido, com nome, @, dominio.
8 - Preenchido com sucesso.

9 - No campo de "Senha" inserir uma senha válida, com no mínimo 6 caracteres.
9 - Preenchido com sucesso.

10 - No campo de "Confirme a Senha" inserir a senha igual a do campo "Senha".
10 - Preenchido com sucesso.

11 - No campo de CPF inserir no campo um CPF válido, sem cararteres especias e/ou letras.
11 - Preenchido com sucesso.

12 - No campo de Sexo, selecione uma das opçãoes, Feminino/Masculino.
12 - Selecionado com sucesso.

13 - No campo "Data de nascimento" preencher com uma data valida, apenas números.
13 - Preenchido com sucesso.

14 - No campo "Telefone" preencher com um telefone valdio, aceitar apenas números, telefone fixo, ou telefone móvel.
14 - Preenchido com sucesso.

15 - No campo de CEP, inserir um CEP válido, apenas números e um CEP existente.
15 - Prenchido com sucesso.

16 - Preencher "Estado" com valor válido.
16 - Preenchido com sucesso.

17 - No campo "Cidade" preencher com um valor válido.
17 - Preenchido com sucesso.

18 - No campo de Bairro Preencher com um valor válido.
18 - Preenchido com sucesso.

19 - No campo de "Endereço" preencher com um valor válido.
19 - Preenchido com sucesso.

20 - No campo de número, preencher com um valor válido.
20 - Preenchido com sucesso.

21 - No campo "Complemento" inserir um valor válido.
21 - Preenchido com sucesso.

22 - No campo de "Telefone para contato" preencher com um valor válido.
22- Preenchido com sucesso.

23 - No campo "Ponto de referência" preencher com um valor válido.
23 - Preenchido com sucesso.

24 - Clicar sobre a flag "Desejo receber e-mails de ofertas promocionais da Saraiva" e validar que foi marcada.
24 - Validado com sucesso.

25 - Clicar sobre o botão "Finalizar Cadastro".
25 - Uma mensagem informa que o cadastro foi realizado com sucesso.

26 - Atualizar a página e com todos os campos em branco clicar sobre "Finalizar Cadastro".
26 - Todos os campos obrigatórios se apresentam sinalizados com um asterisco vermelho.

27 - Preencher os campos e não selecionar a flag de aceitar ofertas.
27 - O cadastro é realizado com sucesso.

28 - Preencher os campos e selecionar a flag de aceitar ofertas.
28 - O cadastro é realizado com sucesso.

*002**

002 - Como a "pessoa física" gostaria de buscar e comprar um livro digital:

Descrição: Realizar uma busca e comprar um determinado produto (livro digital) na loja com um perfil de pessoa física.

Pre-requisitos:
1 - Acesso: https://www.saraiva.com.br
2 - Estar logado com uma pessoa física.

Cenário de teste
1 - Acessar a página da Saraiva pela URL: https://www.saraiva.com.br e validar que o endereço é válido.
1 - Página carregada com sucesso.

2 - Acessar o componente de busca, logalizado no centro superior da página.
2 - Localizado com sucesso.

3 - Digitar um produto e clicar em buscar.
3 - A página é recarregada com uma grade de produtos correpondentes.

4 - Válidar que possui título, descrição, vendedor e preço.
4 - Validado com sucesso.

5 - Clicar sobre o botão de "Departamentos" no canto superior esquerdo da página e em seguida em e-books.
5 - Filtro realziado para exibir apenas livros digitais.

6 - Selecionar um dos livros clicando em "Saiba Mais".
6 - Aberto uma nova página com descrição do livro selecionado.

7 - Válidar que a página possui capa do livro, título, autor, marca, preço, opções de pagamento e a opção de comprar.
7 - Validado com sucesso.

8 - Clicar sobre o campo de busca no centro superior da página e realiar uma busca.
8 - Lista de livros exibida.

9 - Abri um livro físico e clicar em comprar
9 - O livro não é adicionado ao carrinho e uma mensagem informa que não é possível adicionar livro fisico e digital no mesmo carrinho.

10 - Clicar em "Comprar" na parte inferior direita da página.
10 - Um modal é apresentado para confirmação da escolha.

11 - Clicar em "Comprar" no modal exibido.
11- A página de "Meu Carrinho" é exibida.

12 - Validar que é o livro, preço e quantidade de livro selecionado.
12 - Validado com sucesso.

13 - Clicar em finalizar compra.
13 - Nova página de pagamento é aberta.

14 - Seleciona uma forma págamento.
14 - Selecionado com sucesso.

15 - Inserir os dados de pagamento em caso de cartão de credito.
15 - Válidado com sucesso.

16 - Concluir em finalizar comprar clicando no botão finalizar.
16 - Válidado com sucesso. Compra realizada.

2. Descreva os bugs encontrados no caso de teste da Story 002.

- Bug: É possível adicionar livro físico e digital ao mesmo carrinho de compra, contradizendo a descrição do Story 002.
- Bug: Ao criar uma conta diz que a mesma não foi criada ao finalizar cadastro, porem os dados a conta foi sim criada.

3. Escreva o BDD de ao menos um casos de teste

Funcionalidade: Como usuário. Eu quero cadastrar uma nova pessoa física. Para controlar comprar e ser notificado sobre promoções de livros.

Cenario: Deve cadastrar uma pessoa física com sucesso
    Dado que eu acesso o site de cadastro da Saraiva 
    E que eu escolha a opção de Cadastro
    E que eu escolha a opção não Sou Cliente
    E que eu preencha os dados pessoas de pessoa física
    Quando eu confirmar Finalizar Cadastro
    Então meu cadastro será finalizado com sucesso
    E vou ver uma mensagem de sucesso

4. Faça a automação do cadastro na loja:
Criação de automação com uso de MyEclipse, selenium webdriver, com BDD em java.
WebDriver utilizado foi a versão: ChromeDriver 79.0.3945.36
