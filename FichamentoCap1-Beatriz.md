# Ciência de Dados para Negócios

# Universidade Federal da Paraíba

## Atividade I

Leitura e fichamento do capítulo I - Livro: Big Data
Concepts, Technology, and Architecture

**Introduction to the World of Big Data**

Balamurugan Balusamy, Nandhini Abirami. R, Seifedine Kadry, and Amir H. Gandomi

**Aluno**: Beatriz Gonçalves Bento

**Matrícula**: 20220007472

# Introdução

## 1.1 Entendendo Big Data

Diante do crescimento exponencial de dados, indo de 600 MB nos anos 1950s para 100.000.000.000 MB em 2010, criou-se um termo novo para esse fenômeno: *big data*. O termo não tem tradução adequada para o português (dados "grande", ou conjunto grande de dados), então adota-se o nome em inglês.

## 1.2 A evolução do Big Data

"Big data" surgiu como termo em 1997 pela Nasa, mas seu significado foi ampliado por McKinsei para incluir os dados da web. Os 3 Vs do Big Data foram atribuídos por Doug Laney:
- Velocidade;
- Volume;
- Variedade.

O ciclo de processamento do Big Data consiste em:
- Aquisição;
- Preprocessamento;
- Armazenamento e Administração;
- Privacidade e segurança;
- Análise;
- Visualização.

## 1.3 Falhas nos bancos de dados tradicionais

RDBMS (relacionais) não conseguem processar o big data satisfatoriamente, pois suportam até terabytes apenas, são centralizados, comportam dados estruturados, com esquema estático, etc.   

## 1.4 Os 3 Vs do Big Data

### 1.4.1. Volume: 
- De gigabytes a yottabytes (1 YB ≈ 1.000.000.000.000.000 GB);
- Fontes principais: 
  - Social media;
  - Transações de vendas;
  - Bancos online;
  - Sensores de GPS;
  - Sensores em veículos;
  - IOT.

### 1.4.2. Velocidade:
De geração (muitas vezes em streaming) e de processamento.

### 1.4.3. Variedade:
Os tipos de dados são variados, podendo ser Estruturados, Semiestruturados ou Não-estruturados. No caso, o Big Data possui mais deste último tipo.

## 1.5 Fontes do Big Data

Sensores, sistemas de saúde, caixas pretas de aeronaves / helicópteros e jatos, dados web e dados organizacionais.

## 1.6 Diferentes tipos de dados
- Estruturados (tabelas bem definidas)
- Semiestruturados (JSON, XML, etc)
- Não-estruturados (e-mail, postagens, imagens, vídeos, etc.)


## 1.7 Infraestrutura do Big Data
- Hadoop da Apache (framework): "nodes", write-once read-many-times
- HDFS / NoSQL (armazenamento)
- MapReduce / YARN (processamento)


Tudo isso para revelar conhecimento.

## 1.8 O ciclo de vida do Big Data

Os benefícios do Big Data só podem ser explorados com tecnologia e infraestrutura específica, seguindo uma ordem de etapas para o aproveitamento do conjunto gigantesco de dados. O autor apresenta esse ciclo em um esquema ilustrado claro, que vai desde a captura, passando pela transformação, até o consumo dos dados. As principais etapas destacadas são:

### 1.8.1. Geração de Big Data
De todas as fontes citadas anteriormente, nos três tipos de dados também já citados.

### 1.8.2. Agregação
Da aquisição, passando pelo preprocessamento, para o armazenamento dos dados. O preprocessamento é indispensável, com veremos a seguir.

### 1.8.3. Preprocessamento  
Etapa muito importante e indispensável, envolve os seguintes processos com os dados:
- **Integração**: Unificar padrões diferentes;
- **Limpeza**: Remover redundâncias (que muitas vezes surgem depois da integração) e preencher campos faltantes (através de regressão, clustering, binning ou inspeção manual);
- **Redução**: Diminuição do número de atributos (removendo irrelevantes ou redundantes), usando técnicas como compressão de dados, redução de dimensionalidade e de numerosidade, sendo reversível ou não.
- **Transformação**: ETL; suavização (limpar ruído), agregação (exemplo: lucro diário é convertido para lucro mensal ou anual), generalização (exemplo: usar cidade em vez de rua) e discretização (dados crus convertidos para intervalos).

### 1.8.4. Análise de Big Data (Analytics)

Não basta coletar, preprocessar e armazenar os dados. Tem que saber analisá-los, com ferramentas de análise, tais como de regressão, aprendizado de márquina, etc. São as análises descritivas, preditivas e prescritvas.

### 1.8.5. Visualização de Big Data

Há várias formas de apresentar dados visualmente: gráficos de linha, de barra, de disperção, de bolhas, os quais o autor define resumidamente.

## Tecnologia de Big Data
A tecnologia tem contribuído muito para se obter insights de dados. Novas técnicas surgiram, melhorando a eficiência no processamento e na análise dos dados. O autor cita mais uma vez o  Apache Hadoop (armazena e processa dados), o MapReduce, o HDFS, o YARN e o Hadoop Common, detalhando um pouco mais a conexão entre eles. 

### 1.9.1. Desafios enfretados pela tecnologia do Bid Data

O autor apresenta os principais desafios do big data: Heterogeneidade e incompletitude, volume e velocidade, armazenamento, e privacidade.

### 1.9.2. Heterogeneidade e Incompletude
Valores faltantes, ou formatos variados de dados podem dificultar ou até impossibilitar uma análise adequada e proveitosa.

### 1.9.3. Volume e velocidade dos dados

Um bom exemplo é o de transações de cartão de crédito, nas quais a segurança em tempo real é crucial, onde se deve declinar suspeitas de atividades fraulentas rapidamente, apesar quantidade gigantesca de transações ocorrendo por segundo.

### 1.9.4. Armazenamento de dados

A crescente quantidade de dados complexos, como de redes sociais e streaming, exige mecanismos de armazenamento escaláveis, confiáveis e tolerantes a falhas, capazes de acomodar e recuperar informações para análises, como histórico de compras, transações financeiras e registros médicos.

### 1.9.5. Privacidade dos dados

O aumento do volume de dados traz preocupações com a privacidade, exigindo controle de acesso deliberado durante todo o ciclo de vida dos dados. É essencial equilibrar o compartilhamento e a segurança, protegendo informações sensíveis, como transações financeiras e registros médicos, ao fornecer dados para análise.

## 1.10 Aplicações de Big Data

Aplicações do Big Data incluem: detecção de fraudes no setor bancário, análise de dados médicos para diagnóstico precoce, estratégias de marketing baseadas no histórico de compras, análise de dados da web para publicidade personalizada, melhoria de atendimento em call centers, otimização agrícola com sensores, e reconhecimento facial em smartphones para segurança e acesso.

## 1.11 Casos de uso de Big Data
### 1.11.1. Saúde

 O big data revoluciona a saúde ao facilitar o armazenamento e análise de dados complexos, como EHRs e sinais biomédicos, com tecnologias como Hadoop. Isso permite monitoramento remoto, diagnósticos baseados em evidências e decisões em tempo real, melhorando a prevenção de doenças, gestão da saúde e alertas de epidemias, além de reduzir custos e aumentar a eficiência nos serviços médicos.

### 1.11.2. Telecomunicações

O big data impulsiona o setor de telecomunicações ao otimizar a qualidade do serviço, analisar tráfego de rede, detectar fraudes em tempo real e personalizar planos com base no comportamento do cliente. Isso melhora o atendimento, reduz custos, previne *churn*, identifica oportunidades de vendas cruzadas e prevê receitas de novos produtos. Além disso, a análise de dados aprimora a performance da rede, resolve problemas em tempo real e otimiza estratégias de marketing e vendas, aumentando a receita e a competitividade.

### 1.11.3. Serviços de finanças

O big data transforma os serviços financeiros ao otimizar a gestão de riscos, como liquidez, operações e mercados incertos, com soluções em tempo real. Ele avalia a concessão de crédito com base em comportamentos sociais e transacionais, detecta fraudes com análises preditivas em dados de múltiplas fontes e melhora o atendimento ao prever e resolver problemas. Além disso, oferece insights para consultores de investimentos e auxilia na retenção de clientes, personalizando ofertas e monitorando preferências em mercados competitivos.