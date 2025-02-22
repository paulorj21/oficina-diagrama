
# Modelo EER de uma Oficina

### Esquema conceitual de uma oficina fictícia em modelo EER criado para fins didáticos.

Projeto conceitual de um Banco de Dados feito para o desafio de projeto **"Construindo um Esquema Conceitual para Banco De dados"** da plataforma DIO.


## Narrativa

#### **Sistema de cotrole e gerenciamento de ordens de serviço de uma oficina mecânica**
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas

- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega

- A partir da OS, calcula-se o valor de cada serviço, consultando uma tabela de referência de mão-de-obra

- O valor de cada peça também irá compor a OS

- O cliete autoriza a execução dos serviços

- A mesma equipe avalia e executa os serviços

- Os mecânicos possuem código, nome, endereço e especialidade

- Cada OS possui: número, data de emissão, valor, status e data de conclusão

- Uma OS pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS

- Uma OS pode ter vários tipos de peças e um tipo de peça pode estar presente em mais de uma OS
