# 🌍 SOS Localiza

Sistema inteligente para prevenção e resposta a desastres naturais, com foco em alagamentos e enchentes em áreas urbanas vulneráveis.

---

# 🧠 Componente de Inteligência Artificial

## 📌 1. Introdução

O projeto **SOS Localiza** tem como objetivo auxiliar na prevenção e resposta a eventos climáticos extremos, como enchentes e alagamentos, por meio de uma plataforma digital integrada ao Oracle APEX.

A solução permite visualizar áreas de risco, enviar alertas e melhorar a comunicação com órgãos responsáveis. Para tornar o sistema mais eficiente, foi incorporado um componente de Inteligência Artificial (IA) capaz de prever situações de risco com antecedência.

---

## 🎯 2. Problema de IA

O sistema busca resolver o seguinte problema:

> Predizer áreas com risco de alagamento com base em dados meteorológicos e ambientais.

Diferente de soluções reativas, o SOS Localiza utiliza IA para antecipar cenários críticos, permitindo ações preventivas.

A IA é responsável por:
- Analisar dados ambientais
- Identificar padrões de risco
- Classificar regiões com base no nível de perigo
- Apoiar a visualização no mapa interativo

---

## 🤖 3. Modelo de IA

Foi escolhido o uso de:

> Machine Learning supervisionado para predição de risco de alagamento

### ✔ Justificativa

- O problema envolve dados históricos e estruturados  
- Existe relação entre variáveis ambientais e alagamentos  
- Permite previsões baseadas em padrões aprendidos  

### ✔ Modelos sugeridos

- Random Forest (principal)
- Árvores de decisão
- Regressão

O modelo Random Forest foi escolhido por:
- Alta precisão
- Boa performance com múltiplas variáveis
- Baixo risco de overfitting

---

## 📊 4. Dados Utilizados

A IA utiliza diferentes tipos de dados:

### 🌧️ Dados meteorológicos
- Volume de chuva
- Intensidade
- Histórico de precipitação

### 🌍 Dados geográficos
- Altitude
- Tipo de solo
- Proximidade de rios

### 📍 Dados de localização
- Latitude e longitude

### 🔹 Origem dos dados
- APIs públicas de clima
- Bases governamentais
- Dados simulados (MVP)

### 🔹 Formato
Dados estruturados em tabelas no Oracle Database:

| Latitude | Longitude | Chuva (mm) | Altitude | Risco |
|----------|----------|------------|----------|-------|

---

## 🔄 5. Arquitetura e Fluxo de Dados

A solução é composta por:

- Oracle APEX (interface)
- Oracle Database (armazenamento)
- Modelo de IA (processamento)

### 🔹 Fluxo

1. Usuário acessa o sistema
2. APEX coleta localização
3. Dados ambientais são obtidos
4. Informações são enviadas para a IA
5. IA processa e gera previsão
6. Resultado é salvo no banco
7. APEX exibe alertas e mapa

---

## ⚙️ 6. Funcionamento da IA

A IA atua da seguinte forma:

1. Recebe dados de entrada (clima + localização)
2. Analisa padrões aprendidos
3. Classifica o risco da região

### 🔹 Saída da IA

- Baixo risco
- Médio risco
- Alto risco

Esses dados são utilizados para:
- Alertas ao usuário
- Visualização no mapa
- Apoio à tomada de decisão

---

## 🧩 7. Integração com Oracle APEX e Database

A integração ocorre por meio do banco de dados:

### 🔹 Estrutura

- APEX → Interface e interação
- Database → Armazenamento
- IA → Processamento externo

### 🔹 Comunicação

- APEX envia dados → Database  
- IA lê dados → Database  
- IA processa → salva resultado  
- APEX consulta → exibe ao usuário  

Essa abordagem garante:
- Escalabilidade
- Organização
- Facilidade de manutenção

---

## 📌 8. Considerações Finais

A utilização de Inteligência Artificial transforma o SOS Localiza em uma solução preditiva, capaz de antecipar riscos e reduzir impactos de desastres naturais.

Com o uso de Machine Learning supervisionado, o sistema:

- Melhora a prevenção de eventos críticos
- Apoia decisões estratégicas
- Aumenta a segurança da população

A integração com Oracle APEX e Oracle Database garante uma solução robusta, escalável e aplicável em cenários reais.

---

# 🚀 Tecnologias Utilizadas

- Oracle APEX
- Oracle Database
- Machine Learning
- APIs de dados meteorológicos

---

# 📂 Como Executar o Projeto

*(Adicionar instruções conforme implementação)*

---

# 📽️ Vídeo Pitch

*(Inserir link do YouTube aqui)*

---

# 📁 Repositório

*(Inserir link do GitHub aqui)*
