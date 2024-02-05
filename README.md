# Teste de CRUD para uma Plataforma de Acompanhantes 

## Contexo

Você está criando para um painel de administração para uma plataforma de acompanhates. Nesse painel você deve gerir todos os cadastros das acompanhantes da plataforma. Separado em partes tem os requisitos para você seguir. O objetivo deste projeto é avaliar o desenvolvimento de uma aplicação básica de CRUD.


## Requisitos do projeto
### Gerais
   - O projeto deve ter um README.md com todas as instruções sobre como executar e testar o projeto
   - O projeto deve utilizar Git como ferramenta de controle de versão
   - *Possuir testes automatizados é um diferencial*
   - *Estratégias de SEO são um diferencial*

### Funcionais
   1. Administrar acompanhantes:
      - O sistema deverá ter um cadastro de acompanhantes
      - O sistema deverá ser capaz de criar, excluir e alterar (parcialmente ou completamente) as acompanhantes
      - Deve ser possível inativar uma acompanhante (o registro continua, mas com status inativo)
      - A acompanhante deve ter um ID único no sistema para controle interno
      - Cada acompanhante deve ter nome, CPF, RG, data de nascimento, email, telefone, endereço e suas caracteristicas.
      - Todos os campos são obrigatórios, exceto email e telefone.
      - É obrigatório ter um email OU um telefone.
      - Não pode haver dois acompanhantes com o mesmo CPF

### Não-funcionais
   1. O sistema deverá armazenar as informações em um banco de dados
      - Poderá ser utilizada uma base de dados no Docker ou em memória local usando JSON.
   2. O sistema deve conter Testes unitários *(opcional)*
      - Utilize o Jest (já no projeto) para os testes unitários. Quanto maior o coverage, melhor a nota :).
   3. O sistema deve conter uma forma de validar o funcionamento *(opcional)*
      - Use o Swagger (configuração no projeto), postman ou, no mínimo, um .txt com a descrição das rotas.

### Parte 1: Cadastro da Acompanhante
1. Crie uma página de cadastro de acompanhantes onde o administrador do sistema pode inserir as seguintes informações:
   - Nome da modelo
   - Caracteristicas da modelo (idade, peso, cabelo, corpo, etc.)
   - Cachê (preço por hora)
   - Região de atendimento (cidade ou área)
   - Opção de atendimento (casa do cliente, atendimento no local ou em hotéis)
   - Faça o upload de pelo menos uma foto da modelo

### Parte 2: Listagem das Acompanhantes
2. Crie uma página de listagem de acompanhantes onde o administrador pode ver uma lista de todos as acompanhantes cadastradas. A lista deve incluir o nome, a idade e a cidade/região de atendimento de cada modelo.

### Parte 3: Edição das Acompanhantes
3. Adicione uma funcionalidade que permita ao administrador editar as informações de um modelo existente. Isso deve incluir a possibilidade de editar todas as informações mencionadas na Parte 1, incluindo o upload de novas fotos se necessário.

### Parte 4: Exclusão das Acompanhantes
4. Implemente a capacidade de excluir um modelo da plataforma. Ao excluir um modelo, todas as informações associadas a ele devem ser removidas do sistema.

**Instruções e Notas:**
- Você deve criar essa plataforma em uma linguagem de programação de sua escolha e você não precisa de  usar um banco de dados para armazenar as informações das acompanhantes, você poderá usar o local storage ou json simulando API.
- Certifique-se de incluir validações adequadas para garantir que os dados inseridos sejam consistentes e seguros.
- O upload de fotos deve seguir as melhores práticas de segurança e armazenamento de imagens.
- Você tem a liberdade de projetar a interface do usuário da plataforma de acordo com sua preferência.

 #### Avaliação
 - O teste deve ser clonado em seu repositório do Github e, após finalizado, a URL do repositório deverá ser enviada para o contato que lhe enviou o teste
 - Uma breve explicação das decisões tomadas deverá ser enviada para nós, da forma que for acordado entre você e quem lhe enviou o desafio.
 - A avaliação ocorrerá com base na arquitetura, design e qualidade do código, entendimento das regras de negócio, tolerância a falhas e o quão preparado esse serviço estaria para ser rodado em produção.
 - Existem algumas funcionalidades adicionais. Apesar de não serem obrigatórias, terão peso considerável na avaliação.

**Boa sorte.**
