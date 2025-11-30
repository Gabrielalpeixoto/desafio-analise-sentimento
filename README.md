# 🧠⚖️ Azure Speech Studio & Language Studio  
### Anotações, Reflexões e Insights.

Este repositório reúne meus estudos, práticas e percepções desenvolvidas durante meu bootcamp focado no uso das ferramentas **Azure Speech Studio** e **Azure Language Studio**, especialmente voltadas para **análise de fala** e **processamento de linguagem natural (NLP)**.

Como profissional do Direito em migração para Tecnologia, busco conectar a lógica jurídica com soluções inteligentes baseadas em IA — seja para automatizar tarefas, analisar documentos, extrair insights ou simplesmente entender melhor como máquinas interpretam linguagem humana.

---

## 📌 Sumário

1. [Introdução](#introdução)
2. [Ferramentas Estudadas](#ferramentas-estudadas)
3. [Azure Speech Studio](#azure-speech-studio)
   - [Objetivos da Ferramenta](#objetivos-da-ferramenta)
   - [Experimentos Realizados](#experimentos-realizados)
   - [Insights Obtidos](#insights-obtidos)
4. [Azure Language Studio](#azure-language-studio)
   - [Objetivos da Ferramenta](#objetivos-da-ferramenta-1)
   - [Experimentos Realizados](#experimentos-realizados-1)
   - [Insights Obtidos](#insights-obtidos-1)
5. [Casos de Uso Práticos Aplicados ao Direito e Tecnologia](#casos-de-uso-práticos)
6. [Desafios Encontrados](#desafios-encontrados)
7. [Conclusões Gerais](#conclusões-gerais)

---

## 🏁 Introdução

Durante o bootcamp, meu foco foi compreender como aplicar ferramentas de IA da Azure para transformar dados de voz e texto em informações úteis.  
A proposta era não apenas dominar as plataformas, mas também **entender as limitações, boas práticas e possibilidades reais de aplicação**, especialmente pensando em usos jurídicos e corporativos.

---

## 🛠️ Ferramentas Estudadas

- **Azure Speech Studio**  
  Voltado para transformação e análise de áudio: transcrição, identificação de locutor, conversão texto-fala e detecção de sentimentos.

- **Azure Language Studio**  
  Focado em análise textual: extração de entidades, análise de sentimento, classificação, tradução e sumarização.

---

## 🎤 Azure Speech Studio

### 🎯 Objetivos da Ferramenta
- Converter fala em texto (Speech-to-Text)
- Criar modelos personalizados de transcrição
- Detectar emoções na fala
- Fazer análise de conversas (Call Center e reuniões)
- Gerar fala natural a partir de texto (Text-to-Speech)

### 🧪 Experimentos Realizados
- Testei a **transcrição de áudios reais**, incluindo:
  - mensagens de voz
  - trechos de reuniões
  - gravações com ruído e diferentes sotaques
- Treinei um **modelo customizado** com vocabulário jurídico.
- Explorei a **Conversational Analysis**, que identifica:
  - interrupções  
  - tempo de fala por participante  
  - “visão geral” do sentimento da conversa  

### 💡 Insights Obtidos
- A customização com termos jurídicos melhora *drasticamente* a precisão da transcrição.
- O Speech Studio lida bem com sotaques, mas ruídos ainda prejudicam bastante.
- A detecção de emoções funciona, mas deve ser interpretada com cautela — lembra muito uma “indicação”, não um laudo.
- Para uso profissional (ex.: audiências ou entrevistas), a privacidade e LGPD precisam ser consideradas desde a concepção do projeto.

---

## 📝 Azure Language Studio

### 🎯 Objetivos da Ferramenta
- Analisar textos com IA (NLP)
- Identificar entidades importantes (pessoas, datas, leis, organizações etc.)
- Classificar textos automaticamente
- Sumarizar documentos longos
- Detectar sentimentos e opiniões
- Traduzir conteúdos

### 🧪 Experimentos Realizados
- Extração de entidades de petições e contratos.
- Classificação de e-mails por assunto.
- Sumarização de decisões judiciais extensas.
- Desenvolvimento de um pequeno *custom classifier* para separar:
  - documentos jurídicos
  - documentos administrativos
  - comunicações internas

### 💡 Insights Obtidos
- A sumarização foi a função mais poderosa para mim: reduz textos de 20 páginas a parágrafos bem estruturados.
- A extração de entidades identifica leis e datas com boa precisão — extremamente útil.
- Classificadores customizados exigem amostras bem pensadas; garbage in = garbage out.
- O modelo se confunde com textos excessivamente técnicos sem treinamento adicional.

---

## ⚖️💻 Casos de Uso Práticos

Aplicações que visualizei para área jurídica e corporativa:

### • Transcrição e organização de audiências  
Conversão automática do áudio em texto estruturado ou sumarizado.

### • Leitura automática de contratos  
Extração de cláusulas, prazos, partes, valores e riscos.

### • Análise de atendimentos de clientes  
Detecção de sentimentos e problemas recorrentes.

### • Classificação de documentos  
Separar automaticamente:
- peças processuais  
- provas  
- e-mails  
- comunicados internos  

### • Sumarização de documentos extensos  
Acelerar leitura de laudos, petições e relatórios corporativos.

---

## ⚠️ Desafios Encontrados

- Precisão variável dependendo do sotaque e da qualidade do áudio.
- Entendimento insuficiente em textos jurídicos sem treinamento especializado.
- Barreiras de privacidade (LGPD) exigem planejamento e anonimização.
- Customização de modelos consome tempo e exige mais dados do que eu previa.
- Inglês tem suporte ligeiramente superior em relação ao português.

---

## 🧩 Conclusões Gerais

Dominar o Azure Speech Studio e o Language Studio abriu uma nova perspectiva sobre como IA pode **eliminar tarefas repetitivas** e **elevar a produtividade jurídica**.  
Como advogada migrando para tecnologia, percebo que essas ferramentas são pontes poderosas entre:

- linguagem natural  
- automação  
- análise inteligente  
- eficiência operacional  

Elas não substituem a análise humana — mas ampliam enormemente nossa capacidade.

… é só pedir!  
