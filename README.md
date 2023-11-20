# IDEA-Tool
IDEA-Tool é um protótipo de software baseado na abordagem IDEA (extractIon of knowleDge graphs basEd on Artificial intelligence) que tem o objetivo de extrair e interligar grafos de conhecimento, apoiado por um modelo de linguagem de IA, a partir de textos não estruturados.

# Descrição do Projeto
Projeto de pesquisa acadêmica para criar grafos de conhecimento a partir de textos.

# Fonte da Base de dados Textuais para Treinamento
- 

# Pré-requisito
Este projeto possui as seguintes dependências:

- [Python 3.10.12] (https://www.python.org/downloads/release/python-31012/) linguagem de programação para rodar as bibliotecas e desenvolvimento.
- [Google Colab Pro] é um ambiente que oferece essa abordagem de Notebooks cujo objetivo é rodar códigos escritos em Python.
- [GraphDB 9.11] (https://www.ontotext.com/products/graphdb/graphdb-free/) é um banco de dados para lidar com Grafos que permite a manipulação de dados baseados em Grafos RDF e utiliza a linguagem SPARQL para recuperação e processamento de consultas. Além disso, é uma ferramenta que possibilita a descoberta de conhecimento a partir de inferências das relações dos recursos.

- Bibliotecas: 
- [SpaCy 3.5] é uma biblioteca de aprendizado de máquina.  
- [Pipeline] pt_core_news_sm (https://spacy.io/models/pt)
- [Arquitetura] spacy-transformers.TransformerModel.v3 (https://spacy.io/universe/project/spacy-transformers)
- [Modelo de linguagem] neuralmind/bert-base-portuguese-cased (https://github.com/neuralmind-ai/portuguese-bert)

# Experimento
- Para executar o experimento é importante seguir o passo a passo das ações do caderno do projeto.
- 1) Recuperar o Glossário de Termos do EB (link: https://bdex.eb.mil.br/jspui/bitstream/123456789/298/1/C-20-1.pdf)
- 2) Rodar as operações de:
- 2.1) Etapa 1: Pré-anotação (IDEA-C2-Metamodel - Entity e Relations) - Gerar arquivos JSONL para curadoria no Doccano
- 2.1) Etapa 2: Recuperar documentos curados no Doccano (JSONL) para gerar arquivo .SpaCy;
- 2.2) Etapa 2: Rodar NER;
- 2.3) Etapa 3: Rodar RE;
- 2.4) Etapa 4: Rodar NE + RR;
- 2.5) Arquivo de saída: arquivos já triplificado (sujeito, predicado e objeto) para ser importado no repositório no GraphDB: saida.n3

# Trabalhos e publicações
- Projeto de pesquisa.
