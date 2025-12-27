<img src="./img/gif v1.gif" min-width="400px" max-width="400px" width="400px" align="right" alt="Computador iuriCode">
<p>
  <div align="right"> 
<a href="./readme.md"> <img src="./img/LogoUK.png" alt="Logo UK" width="30"/></a><a href="./leiame.md"> <img src="./img/logoBrazil.png" alt="Logo Brasil" width="30"/> </a>
</div>
  <H1><b> Victor Sérgio Silva Barros </b> </H1>
  
</p> 

<img src="./img/dio.png" alt="Logo DIO" width="200"/>
<img src="./img/neo4jLogo.png" alt="Logo Neo4j" width="200"/>

# Treinamento Neo4j - Análise de Dados com Grafos

Este repositório contém materiais e exercícios relacionados ao treinamento Neo4j - Análise de Dados com Grafos oferecido pela [DIO](https://web.dio.me/track/neo4j-analise-de-dados-com-grafos).

## Descrição

O treinamento Neo4j - Análise de Dados com Grafos visa capacitar profissionais no uso de bancos de dados de grafos para análise de dados, cobrindo desde conceitos básicos de teoria dos grafos até técnicas avançadas de consulta e análise usando Neo4j. Este bootcamp enfatiza aplicações práticas em áreas como redes sociais, detecção de fraudes e sistemas de recomendação.

## Desafio: Modelagem de Dados em Grafos para um Serviço de Streaming

Este repositório implementa o desafio do projeto do treinamento Neo4j - Análise de Dados com Grafos, focando no design e implementação de um esquema de banco de dados de grafos para um serviço de streaming (semelhante ao Netflix ou plataformas similares). O desafio demonstra como os bancos de dados de grafos podem modelar efetivamente relacionamentos complexos em dados de entretenimento, permitindo análises avançadas, recomendações personalizadas e consultas eficientes.

### Objetivos
- Aplicar princípios de modelagem de dados de grafos usando Neo4j para representar entidades de serviço de streaming e seus relacionamentos.
- Projetar um esquema de grafo abrangente que capture interações do usuário, metadados de conteúdo e detalhes da plataforma.
- Implementar importação de dados, consulta e análise usando Cypher.
- Demonstrar as vantagens dos bancos de dados de grafos para sistemas de recomendação e análises baseadas em relacionamentos.

### Componentes Principais
- **Entidades (Nós)**:
  - **Usuário**: Propriedades incluem ID, nome, email e tipo de assinatura.
  - **Filme/Série**: Propriedades incluem ID, título, ano de lançamento, duração e classificação.
  - **Ator**: Propriedades incluem ID, nome e data de nascimento.
  - **Diretor**: Propriedades incluem ID e nome.
  - **Gênero**: Propriedades incluem ID e nome.
  - **Plataforma/Dispositivo**: Propriedades incluem ID e tipo (ex.: móvel, TV).

- **Relacionamentos**:
  - `Usuário ASSISTIU Filme` (com propriedades: data assistida, classificação do usuário, tempo assistido).
  - `Ator ATUOU_EM Filme`.
  - `Diretor DIRIGIU Filme`.
  - `Filme PERTENCE_A Gênero`.
  - `Usuário ASSINOU Plataforma`.
  - `Filme SEMELHANTE_A Filme` (para algoritmos de recomendação).

### Detalhes da Implementação
- **Importação de Dados**: Utiliza comandos Cypher LOAD CSV para popular o grafo com dados de exemplo.
- **Consultas e Análises**: Inclui consultas Cypher para histórico de visualização do usuário, recomendações de conteúdo baseadas em similaridades de usuários ou gêneros, análise de colaborações de atores e métricas de popularidade de gêneros.
- **Ferramentas Utilizadas**: Neo4j Desktop ou AuraDB, linguagem de consulta Cypher e opcionalmente scripting em Python com neo4j-driver.
- **Melhores Práticas**: O modelo adere às convenções do Neo4j, garantindo escalabilidade, normalização e travessias eficientes.

### Esquema Visual
Os seguintes diagramas ilustram o esquema de grafo projetado para este desafio:

![Esquema Básico de Grafo](img/job.png)

![Esquema Detalhado de Grafo](img/job1.png)

Essas imagens fornecem uma representação visual dos nós, relacionamentos e propriedades no modelo de dados do serviço de streaming.

## Pré-requisitos

- Conhecimento básico de programação (ex.: Python, Java ou JavaScript)
- Compreensão básica de bancos de dados e estruturas de dados
- Familiaridade com ferramentas de linha de comando ou IDEs como VS Code
- Proficiência em português (já que os materiais do bootcamp estão em português)

## Como Usar

1. Clone este repositório:
    ```sh
    git clone https://github.com/your-username/your-repository.git
    ```
2. Navegue para o diretório do projeto:
    ```sh
    cd your-repository
    ```
3. Siga as instruções em cada módulo para executar os exemplos e exercícios.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Versionamento

1.0.0

## Autor

* **Victor Sérgio Silva Barros**:

<p align="left">
  <a href="mailto:vicssb@gmail.com" alt="Gmail" target="_blank">
  <img src="https://img.shields.io/badge/-Gmail-FF0000?style=flat-square&labelColor=FF0000&logo=gmail&logoColor=white&link=mailto:vicssb@gmail.com" /></a>

  <a href="https://www.linkedin.com/in/victor-sergio-silva-barros/" alt="Linkedin" target="_blank">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/victor-sergio-silva-barros/" /></a>

  <a href="https://wa.me/+5512981328278" alt="WhatsApp" target="_blank">
  <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white&link=https://wa.me/+5512987085327"/></a>

</p>

<p>Siga no GitHub e junte-se a nós!
Obrigado pela visita e bom código!</p>