# -Criando-um-Algoritmo-de-Recomenda-o-de-Musicas-com-Base-em-Grafos-
Primeiro desafio de projeto do Bootcamp Neo4j
🎵 **Queen Music Recommendation**

Sistema de Recomendação Musical utilizando Banco de Dados em Grafos — Neo4j

📌 **Sobre o projeto**

O Queen Music Recommendation é um projeto de estudo desenvolvido como parte do desafio prático da formação DIO, com foco na utilização de bancos de dados em grafos por meio do Neo4j.

A proposta consiste em desenvolver um sistema de recomendação musical capaz de identificar padrões de escuta, preferências e conexões entre usuários, artistas, bandas, músicas e gêneros musicais.

O Queen foi escolhido como estudo de caso, utilizando a trajetória de Freddie Mercury para demonstrar como as relações entre uma banda, seus integrantes, suas composições e a carreira solo de um artista podem contribuir para recomendações personalizadas.

🎯 **Objetivos**

- Representar usuários, artistas, bandas, músicas e gêneros como nós.
- Criar relacionamentos entre os elementos do grafo.
- Registrar interações dos usuários, como escutar, curtir e seguir artistas.
- Utilizar consultas Cypher para filtrar informações e identificar conexões.
- Desenvolver uma lógica de recomendação musical baseada nas preferências dos usuários.
- Demonstrar como bancos de dados em grafos podem ser utilizados em sistemas de recomendação.

🧩 **Modelagem**

O modelo proposto contempla os seguintes nós:

Nó| Descrição
Usuario| Pessoa que utiliza o sistema
Musica| Faixas musicais cadastradas
Artista| Compositores e intérpretes
Banda| Grupos musicais
Genero| Categorias musicais

**Relacionamentos**

- "ESCUTOU": registra quando um usuário escuta uma música.
- "CURTIU": registra músicas apreciadas pelo usuário.
- "SEGUE": representa artistas acompanhados pelo usuário.
- "COMPOS": conecta artistas às músicas que compuseram.
- "INTEGRA": relaciona artistas às bandas.
- "LANCOU": conecta bandas às músicas lançadas.
- "PERTENCE_A": relaciona músicas aos seus gêneros musicais.

Os relacionamentos podem conter propriedades, como quantidade de reproduções, data da última escuta e avaliação do usuário.

🎤 Estudo de caso: Queen e Freddie Mercury

O projeto utiliza o Queen como referência para demonstrar a aplicação das consultas em grafos.

A proposta é identificar:

1. Quais músicas do Queen possuem crédito de composição de Freddie Mercury.
2. Quais músicas pertencem à carreira solo de Freddie Mercury.
3. Quais faixas podem ser recomendadas a usuários que demonstram interesse pelo artista.
4. Quais músicas podem ser sugeridas com base nos gêneros musicais mais escutados ou curtidos.

É importante considerar os créditos individuais de composição, respeitando a participação dos diferentes integrantes do Queen.

💻 **Tecnologias e ferramentas**

- Neo4j: banco de dados orientado a grafos.
- Cypher: linguagem de consulta e manipulação de dados.
- GitHub: hospedagem e documentação do projeto.
- Arrows.app: ferramenta de apoio à modelagem visual de grafos.

🔎 **Consultas e recomendações**

A proposta contempla consultas Cypher para:

- Identificar músicas compostas por Freddie Mercury.
- Consultar o histórico de reprodução dos usuários.
- Encontrar músicas da carreira solo do artista.
- Recomendar faixas de gêneros relacionados às preferências do usuário.
- Identificar padrões de interação com músicas e artistas.

⚠️ **Desafios e dificuldades encontradas**

Um dos principais desafios durante o desenvolvimento deste projeto foi a ausência de um notebook ou computador para utilização das ferramentas necessárias.

Todo o acompanhamento das atividades, estudos, organização das informações e preparação da documentação foi realizado exclusivamente pelo celular.

Essa limitação trouxe dificuldades principalmente na navegação pela plataforma Neo4j AuraDB, na utilização do ambiente de consultas e na organização dos arquivos necessários para o desenvolvimento do projeto.

Mesmo diante dessas limitações, foi possível estudar a proposta, estruturar a modelagem do banco de dados, desenvolver a lógica das consultas e organizar a documentação técnica.

A experiência também demonstrou a importância da adaptação, da autonomia e da continuidade do aprendizado mesmo diante de limitações de recursos.

🚀 **Possibilidades de evolução**

Como melhorias futuras, o projeto poderá receber:

- Cadastro de novos usuários e artistas.
- Ampliação do catálogo musical.
- Histórico de reprodução com informações temporais.
- Recomendações considerando artistas semelhantes.
- Integração com uma interface para apresentação das recomendações.
- Execução e validação das consultas em uma instância Neo4j.

## 📚 Referências

- [Documentação oficial do Neo4j](https://neo4j.com/docs/)
- [Neo4j Graph Examples](https://github.com/neo4j-graph-examples)
- [Arrows.app](https://arrows.app/)
  
👩‍💻 **Considerações finais**

Este projeto representa uma etapa de aprendizado sobre bancos de dados em grafos e suas possibilidades de aplicação em sistemas de recomenda
ção. Aprender também é encontrar caminhos para continuar, mesmo quando os recursos são limitados.
