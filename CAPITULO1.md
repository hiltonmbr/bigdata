# Ciência de Dados para Negócios

# Universidade Federal da Paraíba

## Atividade I

Leitura e fichamento do capítulo I - Livro: Big Data
Concepts, Technology, and Architecture

**Introduction to the World of Big Data**

Balamurugan Balusamy, Nandhini Abirami. R, Seifedine Kadry, and Amir H. Gandomi

**Aluno**: Gabriel Batista Pontes

**Matrícula**: 20220108519

## Instruções

```bash
# clonar o repositório
git clone git@github.com:hiltonmbr/bigdata.git
# criar uma branch com sua matrícula
git checkout -b <sua matrícula>
# Criar o arquivo markdown 
# Copiar e colar o conteúdo do README.md
# Editar o arquivo CAPITULO1.md e salvar commits em sua branch
git push origin <sua matrícula>
# Ao finalizar, abrir um pull request
```


### Fichamento do Capítulo 1: *Big Data: Concepts, Technology, and Architecture*

### Introdução 

O capítulo inicial do livro apresenta uma visão abrangente sobre o conceito de Big Data, suas origens, características, desafios e aplicações práticas. Big Data refere-se a grandes volumes de dados, frequentemente complexos e gerados em alta velocidade, provenientes de diversas fontes, como redes sociais, dispositivos IoT e transações financeiras. Esses dados, muitas vezes não estruturados ou semi-estruturados, ultrapassam a capacidade dos sistemas tradicionais de armazenamento e processamento.

### Origem e Evolução do Big Data

A ideia de Big Data surgiu na década de 1990, quando cientistas da NASA enfrentaram dificuldades para visualizar grandes conjuntos de dados. A partir daí, consultorias como McKinsey definiram os "3 Vs" que caracterizam o Big Data:

- **Volume**: Enorme quantidade de dados gerados continuamente, como os 500 terabytes diários produzidos pelo Facebook.
- **Velocidade**: Ritmo acelerado de geração e processamento de dados, especialmente em situações que exigem respostas em tempo real.
- **Variedade**: Diversidade de formatos de dados, incluindo estruturados, semi-estruturados e não estruturados.

### Limitações dos Sistemas Tradicionais

Os Sistemas de Gerenciamento de Bancos de Dados Relacionais (RDBMS) foram amplamente utilizados no passado, mas possuem limitações significativas ao lidar com Big Data:

- Não conseguem processar grandes volumes de dados em alta velocidade.
- Foram projetados para dados estruturados, mas a maioria dos dados modernos é semi-estruturada ou não estruturada.
- Escalar esses sistemas é caro e pouco eficiente.

### Infraestrutura

Para superar essas limitações, tecnologias como Hadoop, HDFS e MapReduce desempenham um papel crucial:

- **Hadoop**: Framework que permite o armazenamento e processamento de grandes conjuntos de dados em hardware de baixo custo.
- **HDFS**: Sistema de arquivos distribuído que suporta armazenamento escalável.
- **MapReduce**: Modelo de programação para processamento paralelo e distribuído.

### Ciclo de Vida

O ciclo de vida do Big Data envolve as seguintes etapas:

1. **Geração de Dados**: Dados criados a partir de fontes como sensores, redes sociais e registros médicos.
2. **Agregação e Armazenamento**: Coleta, limpeza e organização dos dados em plataformas como HDFS.
3. **Análise**: Utilização de ferramentas como MapReduce para extrair insights.
4. **Visualização**: Representação gráfica dos dados para apoiar a tomada de decisão.

### Desafios

Entre os principais desafios estão:

- **Heterogeneidade e Incompletude**: Dados variados e, muitas vezes, inconsistentes ou incompletos dificultam a análise.
- **Volume e Velocidade**: Requerem infraestrutura escalável e processamento rápido.
- **Privacidade e Segurança**: Proteção de dados sensíveis contra acessos não autorizados.

### Aplicações

Big Data tem transformado diversos setores:

- **Saúde**: Monitoramento remoto de pacientes, diagnóstico precoce e análise de registros médicos.
- **Telecomunicações**: Personalização de ofertas e melhoria da qualidade do serviço.
- **Serviços Financeiros**: Detecção de fraudes, avaliação de crédito e análise de comportamento do cliente.
- **Marketing**: Análise do histórico de compras para prever preferências e personalizar campanhas.
- **Agricultura**: Monitoramento de safras com sensores e otimização da produção.

### Conclusão

Ao final, destaca-se o potencial do Big Data para transformar a forma como as organizações gerenciam informações e tomam decisões. Ao combinar tecnologias avançadas, como Hadoop, com análises sofisticadas, é possível gerar valor estratégico a partir de grandes volumes de dados, explorando insights que antes estavam ocultos.