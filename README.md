![alt text](https://github.com/goomerdev/job-dev-backend-interview/raw/master/media/logo-azul.png "Goomer")

## Challenge - Developer Backend

Você provavelmente já está participando do nosso processo seletivo, mas se você caiu aqui por acaso, leia esse documento até o final e se você se interessar, pode começar o processo à partir daqui =]

Não é esperado que todas as pessoas consigam realizar esse desafio por completo, já que é destinado a todos os níveis de carreira.

A avaliação será baseada na sua capacidade de escrever um código simples, de fácil manutenção, e pela quantidade de funcionalidades que você entregar.

### Instruções

- **Nome do Projeto:** Goomer Lista Rango
- **Objetivo do Projeto:** Criar uma API RESTful capaz de gerenciar os restaurantes e os produtos do seu cardápio.
- **Tecnologia:** Node.js com banco de dados relacional.
- **Entregáveis:** Crie um repositório pessoal para esse projeto, siga as instruções abaixo e responda e-mail recebido com link do repositório. Caso você resolveu fazer o teste por conta própria pode enviar para selecao.tech@goomer.com.br.

### Desafio

- A sua API deverá ser capaz de:
    - Listar todos os restaurantes
    - Cadastrar novos restaurantes
    - Listar os dados de um restaurante
    - Alterar os dados um restaurante
    - Excluir um restaurante
    - Listar todos os produtos de um restautante
    - Criar um produto de um restaurante
    - Alterar um produto de um restaurante
    - Excluir um produto de um restaurante

- O cadastro do restaurante precisa ter os seguintes campos:
    - Foto do restaurante
    - Nome do restaurante
    - Endereço do restaurante
    - Horários de funcionamento do restaurante (ex.: De Segunda à Sexta das 09h as 18h e de Sabado à Domingo das 11h as 20h).
    
- O cadastro de produtos do restaurante precisa ter os seguintes campos:
    - Foto do produto
    - Nome do produto
    - Preço do produto
    - Categoria do produto (ex.: Doce, Salgados, Sucos...)
    - Quando o Produto for colocado em promoção, precisa ter os seguintes campos:
        - Descrição para a promoção do produto (ex.: Chopp pela metade do preço)
        - Preço promocional
        - Dias da semana e o horário em que o produto deve estar em promoção

##### Formato de horários
- É necessário tratar os campos que indicam horários de funcionamento e horário para as promoções dos produtos. 
- Os campos devem possuir o formato `HH:mm`. 
- Os horários devem possuir intervalo mínimo de 15 minutos.

### O que nós vamos avaliar

- Vamos avaliar a qualidade do código, legibilidade e a quantidade de funcionalidades implementadas.
- Você é livre para tomar as decisões técnicas com as quais você se sente mais confortável. Apenas esteja pronto(a) para explicar as razões que fundamentaram suas escolhas =]
- Inclua um arquivo *README* que possua:
  - desafios/problemas com os quais você se deparou durante a execução do projeto.
  - maneiras através das quais você pode melhorar a aplicação, seja em performance, estrutura ou padrões. 
  - todas as intruções necessárias para que qualquer pessoa consiga rodar sua aplicação sem maiores problemas.

### Dicas

- Documente seu projeto em arquivos markdown explicando a estrutura, processo de setup e requisitos.
- Tenha sempre um mindset de usabilidade, escalabilidade e colaboração.
- A organização das branches e os commits no repositório falam muito sobre como você organiza seu trabalho.
- Os testes unitários são mais do que desejados.
- O design/estrutura do código da aplicação deve ser *production ready*.
- Tenha em mente os conceitos de *SOLID, KISS, YAGNI e DRY*.
- Use boas práticas de programação.
- Considere que não sabemos nada sobre os seus conhecimentos, então quanto mais você mostrar e o quão mais descritiva for sua documentação, melhor =]

### FAQ

#### Posso utilizar frameworks/bibliotecas?

Você pode usar bibliotecas como Express, mas queremos que a solução de arquitetura seja sua, portanto não use frameworks que impõem uma arquitetura específica.

#### Quanto tempo eu tenho ?

Quanto mais tempo você demorar, mais críticos seremos na sua avaliação =]

#### Qual banco de Dados devo usar?

Escolha entre MySQL e PostgreSQL. 

#### Posso usar um ORM?

O uso de ORM é permitido apenas para **estabelecer a conexão com o banco de dados.** No entanto, para podermos avaliar os seus conhecimentos em SQL pedimos que **não use ORM nas consultas ao banco.** As bibliotecas normalmente possuem métodos que permitem consultas diretamente em SQL (raw queries) mesmo através do ORM.


### Happy coding 

![alt text](https://github.com/goomerdev/job-dev-backend-interview/raw/master/media/may-the-force-be-with-you.jpg "Happy Coding!!!")
