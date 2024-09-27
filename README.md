
# Projeto de Banco de Dados Hospitalar

Este repositório contém a implementação de um banco de dados completo para um hospital, desenvolvido como parte de um trabalho acadêmico. O projeto foi realizado em duas etapas principais: a modelagem inicial e a implementação final em SQL.

## Descrição do Projeto

O objetivo deste trabalho foi criar, desde o início, um banco de dados para gerenciar as diversas operações de um hospital. Todas as entidades, relacionamentos e atributos foram definidos por nossa equipe. 

### Principais Características:
- **15 Entidades**: Cada uma representando elementos críticos do ambiente hospitalar, como médicos, pacientes, enfermeiros, entre outros.
- **10 Relacionamentos**: Entre as entidades, incluindo agregações, especializações e até mesmo recursões, refletindo a complexidade das operações hospitalares.
- **Modelo ERE**: A primeira fase do projeto envolveu a criação do modelo Entidade-Relacionamento Estendido (ERE), documentando todas as entidades e seus relacionamentos.
- **Implementação em SQL**: Na segunda fase, o modelo ERE foi transformado para o modelo relacional e implementado em SQL, garantindo que todas as restrições, chaves primárias e estrangeiras, e demais regras de negócio fossem contempladas.
- **Script Python**: Além dos modelos anteriores, fizemos a implementação de um código python que consegue consultar, atualizar, deletar e inserir novos itens ao banco
- 
## Estrutura do Projeto

- **/documentação**: Contém a documentação completa do modelo ERE e os diagramas.
- **/tables.sql**: Inclui os scripts SQL utilizados para criar e popular as tabelas do banco de dados.
- **/python.py**: Scripts adicionais para manipulação e consultas ao banco de dados.

## Como Executar

1. Clone o repositório.
   ```bash
   git clone <link-do-repositorio>
   ```
2. Importe o arquivo SQL para seu gerenciador de banco de dados.
   ```bash
   mysql -u <usuario> -p < banco < sql/implementacao.sql
   ```
3. Execute as consultas ou manipulações conforme necessário.

## Contribuidores

Este projeto foi desenvolvido por mim, Gabriel Henrique, Pedro Augusto Vieira e Thalles Felipe
