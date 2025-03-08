# 🧠 Análise de Sentimentos com Azure AI Language Studio

## 📋 Descrição do Projeto

Este projeto demonstra o uso do Azure AI Language Studio para realizar análise de sentimentos em textos relacionados a uma loja de eletrônicos. A análise de sentimentos é uma técnica de processamento de linguagem natural (NLP) que identifica e extrai opiniões subjetivas dentro do texto, classificando-as como positivas, negativas ou neutras.
Configuração do Ambiente.

## ⚙️ Configuração do Ambiente

### 🏗️ Criação de recursos no Azure

Foi criado um recurso de Language Service no Azure.
Configuração realizada na região apropriada com o tier de preço gratuito (F0).

### 🔑 Configuração de Acesso

Foi necessário vincular o recurso a uma conta institucional/corporativa.
Configuração das permissões adequadas (Cognitive Services Contributor).

### 📊 Conjunto de Dados
O conjunto de dados consiste em 10 sentenças relacionadas a experiências de clientes em uma loja de eletrônicos.

## 🔍 Processo de Análise

1. Preparação dos dados:

Criação de um arquivo de texto com as sentenças.
Upload no Language Studio

2. Execução da análise:

Utilização da ferramenta "Sentiment and opinion mining" no Language Studio.
Processamento de texto para identificar sentimentos gerais e aspectos específicos mencionados

3. Avaliação dos resultados:

Interpretação das pontuações de sentimento (positivo, negativo, neutro).
Análise de aspectos específicos mencionados (atendimento, qualidade, preço, etc.)

## 💡 Insights Obtidos
Após analisar as sentenças, alguns insights importantes foram revelados:

Sentimentos sobre Produtos vs. Serviços:

Os sentimentos sobre os produtos físicos tendem a ser mais positivos.
Os serviços (como atendimento ao cliente e políticas de garantia) tendem a gerar mais sentimentos negativos

![sent2](https://github.com/user-attachments/assets/ce8d3689-923c-4944-919a-e1de4cf0ae75)

Polaridade de Aspectos:

"Preço" frequentemente aparece como um aspecto com sentimento negativo.
"Qualidade" e "funcionalidade" geralmente recebem avaliações positivas

![sent3](https://github.com/user-attachments/assets/43d571c3-92fd-4a35-ad7a-e2657ac72822)

Padrões de Linguagem:

Expressões de frustração são facilmente identificadas como negativas.
Comentários neutros são frequentemente relacionados a fatos e comparações

![sent10](https://github.com/user-attachments/assets/dd912cd9-9501-4680-98d4-afbba12e4a5d)

Sentimentos Mistos:

Sentenças que contêm "mas" geralmente expressam sentimentos mistos
O modelo consegue identificar a dualidade em declarações complexas

![sent10](https://github.com/user-attachments/assets/cc3ab9a8-2647-463c-bf98-a49c16c587df)

## 🚀 Possibilidades e Aplicações
A análise de sentimentos com o Azure Language Studio pode ser aplicada em diversos cenários:

Monitoramento de Satisfação do Cliente:

Análise automatizada de avaliações e comentários
Identificação rápida de problemas recorrentes


Insights para Melhorias:

Identificação dos produtos ou serviços que geram mais sentimentos negativos
Detecção de aspectos específicos que precisam de atenção


Análise Competitiva:

Comparação de sentimentos sobre produtos próprios vs. concorrentes
Identificação de vantagens competitivas e pontos fracos


Personalização da Experiência:

Adaptação da comunicação com base no sentimento do cliente
Direcionamento de clientes insatisfeitos para equipes de retenção


Automação de Respostas:

Priorização de respostas para comentários negativos
Encaminhamento automático para departamentos específicos

## ✨ Conclusão

A análise de sentimentos com o Azure AI Language Studio oferece uma forma poderosa de extrair insights valiosos de dados textuais não estruturados. A capacidade de identificar não apenas o sentimento geral, mas também aspectos específicos mencionados, permite uma compreensão mais profunda da experiência do cliente.
Este projeto demonstra como configurar e utilizar essa tecnologia para análise de feedback de clientes em uma loja de eletrônicos, mas as mesmas técnicas podem ser aplicadas em diversos setores e casos de uso.
