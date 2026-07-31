# 🧠 Caderno Temático — IA Generativa e o Futuro do Trabalho no Setor Financeiro

> Projeto do Desafio de Projeto da [DIO](https://www.dio.me/) — uso do NotebookLM como ferramenta de aprendizagem ativa, com curadoria de fontes, engenharia de prompts e produção de um miniguia de estudo.

---

## 📌 1. Contexto e Objetivos

### Por que esse tema?

Sou estudante de Sistemas de Informação e busco constantemente aprimorar meus conhecimentos em tecnologia, acompanhando as inovações que estão transformando o mercado e a forma como as organizações operam. Escolhi o tema **"IA Generativa e o Futuro do Trabalho no Setor Financeiro"** porque ele conecta diretamente três aspectos da minha trajetória:

- Meu objetivo de carreira: atuar em instituições que utilizem a tecnologia para aumentar a eficiência, otimizar processos e desenvolver soluções para problemas reais.
- Meu interesse em compreender como a tecnologia transforma as estruturas de trabalho e o mercado.
- A necessidade de me manter atualizado sobre um tema em constante evolução, contribuindo para análises, discussões e tomadas de decisão mais fundamentadas.

### Objetivos de estudo

Com este caderno temático, pretendo:

- Compreender como a IA generativa está sendo aplicada atualmente em diferentes tipos de instituições financeiras, como bancos, fintechs, seguradoras e gestoras de investimentos, por meio da análise de casos de uso reais.
- Identificar quais funções e cargos tendem a se transformar, desaparecer ou surgir no setor financeiro em decorrência da adoção da IA generativa.
- Mapear as competências técnicas e comportamentais mais valorizadas nesse novo cenário, orientando meu plano de estudos e meu desenvolvimento profissional.
- Analisar os principais desafios e limitações da adoção da IA generativa, incluindo governança, conformidade com a LGPD, alucinações dos modelos e requisitos de compliance.
- Construir um material de referência que possa ser utilizado para revisões futuras e para acompanhar a evolução da IA generativa no setor financeiro.

---

## 📚 2. Curadoria de Fontes

Fontes abertas selecionadas e carregadas no NotebookLM:

|   | Fonte | Tipo | Link |
|---|-------|------|------|
| 1 | Principais tendências bancárias para 2026 | Accenture — Relatório de tendências | https://www.accenture.com/us-en/insights/banking/accenture-banking-trends-2026 |
| 2 | The financial sector in 2026: AI, Open Finance, BaaS, and the trends that are already changing the rules | Vertigo — Artigo/blog corporativo | https://en.vertigo.com.br/The-financial-sector-in-2026%3A-Open-Finance-BAAS-and-its-trends./ |
| 3 | Super agentes de IA: A revolução bancária e financeira em 2025 | GFT Technologies — Artigo/blog corporativo | https://www.gft.com/br/pt/blog/super-agentes-de-ia-a-revolucao-bancaria-e-financeira-em-2025 |
| 4 | IA generativa no setor financeiro: produtividade vs. risco | CESAR — Artigo técnico nacional | https://www.cesar.org.br/w/ia-generativa-no-setor-financeiro-produtividade-vs-risco |
| 5 | IA Generativa e o Trabalho Bancário: o que Diz a OIT | Anjos Ramos Advogados — Artigo (reportando estudo da OIT) | https://anjosramos.com.br/blog/ia-generativa-e-o-trabalho-bancario-o-que-aponta-o-novo-estudo-da-oit/ |
| 6 | Guia orientativo de boas práticas para o uso de sistemas de inteligência artificial | ANBIMA — Guia institucional (PDF) | https://www.anbima.com.br/data/files/63/74/15/39/F12C091039E04909EA2BA2A8/Guia_orientativo_boas_praticas_para_o_uso_de_sistemas_de_inteligencia_artificial.pdf |
| 7 | Global Banking Annual Review | McKinsey & Company — Relatório institucional | https://www.mckinsey.com/industries/financial-services/our-insights/global-banking-annual-review |
| 8 | Rethinking Trust: Generative AI and the Cyber Threat | PwC — Relatório técnico (PDF) | https://www.pwc.com/m1/en/resilience-hub/docs/rethinking-trust-generative-ai-cyber-threat.pdf |
| 9 | AI Baseline Guidance Review — April 2025 | CMORG (Reino Unido) — Guia técnico (PDF) | https://www.cmorg.org.uk/sites/default/files/2025-05/CMORG%20-%20AI%20Baseline%20Guidance%20Review%20-%20April%202025%20-%20TLP%20CLEAR.pdf |
| 10 | Accelerating the Path from GenAI Potential to Profit in Banking | BCG — Relatório institucional (PDF) | https://web-assets.bcg.com/7d/91/7f9d246e4abbafb9c2a3dc74e8ee/accelerating-the-path-from-genai-potential-to-profit-in-banking.pdf |

> Critério de seleção: priorizei fontes com credibilidade institucional
> (organismos internacionais, associações de classe, consultorias globais)
> e diversidade de ângulo — dados de mercado de trabalho, riscos regulatórios,
> visão corporativa e aprofundamento técnico — evitando conteúdo puramente
> promocional.

---

## 🔧 3. Engenharia de Prompts e "Cicatrizes"

### 3.1 Perguntas estratégicas iniciais

Perguntas usadas para mapear o assunto dentro das fontes:

1. Quais são os principais casos de uso de IA generativa no setor financeiro (bancos, fintechs, seguradoras, gestoras), segundo as fontes?
2. Quais funções/cargos no setor financeiro tendem a se transformar, desaparecer ou surgir por causa da IA generativa até 2030?
3. Quais competências técnicas e comportamentais as fontes indicam como as mais valorizadas nesse novo cenário?
4. Quais são os principais riscos e limitações citados para o uso de IA generativa em instituições financeiras?
5. Existe divergência entre as fontes sobre o ritmo ou o impacto dessa transformação? Se sim, qual?
6. De que formas a IA generativa pode apoiar profissionais que já atuam na área de dados/TI hoje, no dia a dia?
7. Como um profissional pode se desenvolver e se diferenciar usando IA generativa como ferramenta de aprendizado e produtividade?

### 3.2 Variações de prompt testadas (mesma pergunta, abordagens diferentes)

Peguei a pergunta sobre **funções impactadas** e testei 3 variações para comparar a qualidade da resposta:

**Versão 1 — genérica:**
```
Quais empregos serão substituídos pela IA no setor financeiro?
```
> **Resposta obtida (NotebookLM):**
>
> De acordo com as fontes, a IA (especialmente a generativa e a agêntica) não
> extinguirá necessariamente profissões inteiras de imediato, mas substituirá
> tarefas específicas, impactando severamente cargos administrativos e de
> processamento de dados padronizados.
>
> **1. Apoio administrativo e escriturários** — escriturários/assistentes
> bancários (redação de documentos-modelo, organização de arquivos) e
> analistas de apoio juniores (limpeza de dados, relatórios básicos).
>
> **2. Atendimento e operações de frente** — caixas de banco, triagem inicial
> de atendimento (substituída por interfaces de linguagem natural) e
> negociadores de dívidas (já assumido por "super agentes" de IA em alguns casos).
>
> **3. Back-office e funções operacionais** — processamento de contratos e
> documentos, e triagem de crédito padrão.
>
> **4. Áreas jurídicas e de compliance** — gestão de litígios de massa
> (defesas padronizadas, monitoramento de prazos) e monitoramento de
> transações para prevenção a fraudes.
>
> A resposta reforça a distinção entre **automação** (substituição total,
> maior risco de realocação/dispensa) e **aumento** (a IA apoia o profissional,
> que passa a atuar como supervisor de sistemas inteligentes). Conclui citando
> o conceito de "**Banco 10x**": uma pessoa, apoiada por agentes digitais,
> entregando o impacto que antes exigia times inteiros.

**Versão 2 — com contexto e formato pedido:**
```
Com base apenas nas fontes carregadas, liste em uma tabela as funções do setor
financeiro com maior risco de automação e as funções com maior potencial de
crescimento, indicando de qual fonte cada informação foi extraída.
```
> **Resposta obtida (NotebookLM):**
>
> | Função / Cargo | Categoria | Fonte |
> |---|---|---|
> | Trabalhadores de apoio administrativo (escriturários e assistentes) | Maior risco de automação | Estudo da OIT citado por Anjos Ramos |
> | Caixas de banco | Maior risco de automação | Estudo da OIT citado por Anjos Ramos |
> | Analistas de apoio (juniores) | Maior risco de automação | Estudo da OIT citado por Anjos Ramos |
> | Atendimento de primeiro nível (triagem básica) | Maior risco de automação | CESAR, Anjos Ramos |
> | Processadores de documentos e faturamento | Maior risco de automação | CESAR |
> | Redatores de documentos-modelo e relatórios padronizados | Maior risco de automação | Anjos Ramos, CESAR |
> | Gerentes de relacionamento | Alto potencial de crescimento/transformação | BCG, Anjos Ramos |
> | Assessores de investimento | Alto potencial de crescimento/transformação | GFT, McKinsey |
> | Desenvolvedores de software e profissionais de TI | Alto potencial de crescimento/transformação | BCG, CESAR |
> | Gestores de "equipes de IA" (conceito do Banco 10x) | Função emergente de crescimento | Accenture |
> | Especialistas em governança, ética e compliance de IA | Função emergente de crescimento | Vertigo, ANBIMA |
> | Analistas estratégicos e gestores de exceções | Alto potencial de crescimento/transformação | CESAR |
> | "Maestros digitais" (orquestradores de agentes de IA) | Função emergente de crescimento | GFT |
> | Equipes especializadas de defesa (cibersegurança e risco) | Alto potencial de crescimento/transformação | Accenture, PwC |
>
> **Observações das fontes:** distinção entre **automação** (substituição total
> em cargos padronizados) e **aumento** (IA ampliando funções que exigem
> contexto, relacionamento e decisão sob incerteza); o conceito do "**Banco 10x**"
> (profissional que gerencia múltiplos agentes de IA em vez de executar
> individualmente); e a observação de que o **back-office** tem o ROI mais
> imediato de automação, enquanto o **front-office** foca em hiperpersonalização.

**Versão 3 — pedindo raciocínio e comparação entre fontes:**
```
As fontes concordam entre si sobre o impacto da IA generativa nos empregos do
setor financeiro? Aponte convergências e divergências entre elas, citando a
origem de cada afirmação.
```
> **Resposta obtida (NotebookLM):**
>
> As fontes apresentam um **consenso fundamental** sobre a transformação do
> trabalho pela IA generativa, mas divergem quanto ao **foco do impacto**
> (econômico vs. social) e à **natureza da mudança** (substituição vs. colaboração).
>
> **Convergências:**
> - Aumento drástico de produtividade (até 25% no *private banking*; 33% de
>   ganho de eficiência no ciclo de desenvolvimento de software em 3 anos).
> - Funções de apoio administrativo (escriturários, caixas, assistentes) são
>   as mais expostas à automação; back-office tem o ROI mais imediato.
> - Necessidade urgente de requalificação (engenharia de prompt, alfabetização
>   de dados, aprendizado contínuo).
> - Migração das equipes humanas de tarefas burocráticas para análise
>   estratégica e gestão de exceções.
>
> **Divergências:**
>
> | Tema | Visão A — Transformação/Lucro | Visão B — Risco/Trabalho |
> |---|---|---|
> | Substituição vs. Aumento | Accenture e GFT: "colegas digitais" e "Banco 10x" ampliando capacidade humana | OIT (via Anjos Ramos): automação de funções inteiras, risco real de deslocamento |
> | Dependência de headcount | Accenture: crescimento não depende mais do número de funcionários | ANBIMA e CESAR: visão mais cautelosa, human-in-the-loop como requisito de segurança |
> | Impacto no front-office | Deloitte (via ANBIMA): potencial de receita adicional por funcionário | McKinsey: ameaça à relação com o cliente, IA agêntica pode desintermediar bancos |
> | Ritmo de adoção | BCG e Accenture: corrida acelerada, "ano dos agentes" | CMORG e PwC: ritmo ditado por mitigação de risco cibernético e regulatório |
>
> **Síntese:** consultorias de negócio (BCG, McKinsey, Accenture) veem a IA
> como ferramenta para "fazer mais com o mesmo (ou menos)"; fontes voltadas a
> trabalho (OIT/Anjos Ramos) e governança (CMORG, ANBIMA) destacam a exposição
> ocupacional e a proteção de direitos dos trabalhadores.

**Aprendizado:** a Versão 1 (genérica) trouxe uma resposta ampla mas sem
rastreabilidade de fonte. A Versão 2 (pedindo tabela + citação por fonte)
resolveu isso "de graça", tornando a auditoria viável mesmo com 10 fontes
carregadas. A Versão 3 (pedindo convergência/divergência entre fontes) foi a
que gerou mais valor analítico: revelou que a "discordância" entre as fontes
não é sobre fatos, mas sobre **ênfase** — consultorias de negócio priorizam
lucro e velocidade, enquanto fontes de trabalho/governança priorizam proteção
e risco. Isso me ensinou que o prompt certo não só melhora a qualidade da
resposta, mas pode revelar a própria estrutura do debate por trás do tema.

### 3.3 Dificuldades encontradas (troubleshooting)

> Como o NotebookLM é fundamentado (grounded) nas fontes carregadas, o problema
> raramente é "alucinação" pura — geralmente são erros de interpretação ou
> respostas rasas quando o prompt não é bem formulado.

- **Rastreabilidade de fonte em respostas genéricas:** na Versão 1 do teste
  de prompt (seção 3.2), a resposta veio corrida, sem indicar de qual fonte
  vinha cada afirmação — com 10 fontes carregadas, ficou inviável rastrear
  manualmente de onde saiu cada informação. Isso só foi resolvido quando o
  prompt foi reformulado (Versão 2), pedindo explicitamente tabela e citação
  por fonte.
  
- **Teste de limite do grounding (pergunta fora do escopo das fontes):**
  ao perguntar especificamente sobre o impacto da IA generativa no setor de
  seguros no Japão — assunto não coberto por nenhuma das 10 fontes —, o
  NotebookLM não inventou uma resposta genérica. Ele reconheceu explicitamente
  que as fontes não tratam do mercado segurador japonês, explicou o que
  realmente estava disponível sobre a região APAC de forma mais ampla
  (investimento em IA, ganhos de eficiência), e ofereceu ativamente buscar a
  informação fora do escopo das fontes carregadas. Isso confirma na prática
  que o grounding do NotebookLM funciona como esperado: ele prioriza admitir
  a limitação a arriscar uma resposta sem base sólida.
---

## 📖 4. Miniguia de Estudo (Entrega Final)


### 4.1 Resumo estruturado

**Panorama geral: como a IA generativa vem sendo adotada no setor financeiro**

A adoção acontece em ritmos diferentes conforme a área. No back-office, a IA
generativa e agêntica já entrega o retorno sobre investimento mais imediato,
automatizando processamento de documentos, faturamento e triagem de crédito
padrão. No front-office, o foco é hiperpersonalização do atendimento e
interações via linguagem natural. Consultorias como BCG e Accenture descrevem
2025-2026 como "o ano dos agentes de IA", com ganhos de produtividade estimados
em até 25% no *private banking* e 33% no ciclo de desenvolvimento de software.

**Impacto nas funções e no emprego no setor financeiro**

Há uma divisão clara entre funções em risco e funções em transformação:
- **Maior risco de automação:** escriturários, assistentes bancários, caixas
  de banco, analistas de apoio juniores e processadores de documentos —
  funções com tarefas altamente padronizadas.
- **Alto potencial de crescimento/transformação:** gerentes de relacionamento,
  assessores de investimento, desenvolvedores de software, analistas
  estratégicos e especialistas em governança de IA — funções que exigem
  contexto, relacionamento e decisão sob incerteza.

Surge também o conceito do "**Banco 10x**": um profissional que gerencia
múltiplos agentes de IA (um "maestro digital"), entregando o impacto que antes
exigia uma equipe inteira.

**Novas competências exigidas**

As fontes convergem na urgência de requalificação: engenharia de prompt,
alfabetização de dados, capacidade de supervisionar e validar o que a IA
produz (em vez de só executar tarefas manualmente), e aprendizado contínuo
como parte da rotina profissional — não mais como algo pontual.

**Riscos, governança e limitações**

Aqui aparece a maior divergência entre as fontes. Consultorias de negócio
(BCG, McKinsey, Accenture) enfatizam velocidade de adoção e ganho de lucro.
Já fontes voltadas a trabalho e governança (o estudo da OIT, ANBIMA, CMORG,
PwC) priorizam riscos regulatórios, cibersegurança e a necessidade de manter
supervisão humana (*human-in-the-loop*) em decisões sensíveis — como crédito,
cobrança e investimento — para evitar vieses discriminatórios e garantir
explicabilidade.



### 4.2 Glossário de conceitos

| Termo | Definição |
|-------|-----------|
| IA Generativa (GenAI) | Modelos de inteligência artificial capazes de criar conteúdo novo (texto, imagem, código) a partir de padrões aprendidos em grandes volumes de dados, em vez de apenas classificar ou prever com base em regras fixas. |
| IA Agêntica / Agentes de IA | Sistemas de IA que vão além de responder perguntas: executam tarefas de forma autônoma, tomam decisões dentro de um fluxo de trabalho e podem interagir com múltiplos sistemas sem supervisão humana constante. |
| RAG (Retrieval-Augmented Generation) | Técnica em que o modelo de IA busca informações em uma base de documentos específica antes de gerar a resposta, aumentando a precisão e reduzindo respostas inventadas — é o princípio por trás do funcionamento do NotebookLM. |
| Automação vs. Aumento | Distinção entre dois efeitos da IA no trabalho: **automação** é a substituição total de uma tarefa ou função pela tecnologia; **aumento** é quando a IA amplia a capacidade do profissional, que continua no centro da decisão. |
| Human-in-the-loop | Princípio de governança em que uma decisão automatizada (ex: aprovação de crédito) exige revisão ou validação humana antes de ser efetivada, especialmente em contextos de risco ou impacto sobre pessoas. |
| Reskilling / Upskilling | *Reskilling* é a requalificação para uma função diferente da atual; *upskilling* é o aprofundamento de competências dentro da própria função. Ambos aparecem nas fontes como resposta necessária à transformação do trabalho pela IA. |
| Engenharia de Prompt | Prática de estruturar as instruções dadas a um modelo de IA (contexto, formato, exemplos) para obter respostas mais precisas e úteis — testada diretamente neste projeto na seção 3.2. |
| "Banco 10x" | Conceito (citado pela Accenture) em que um único profissional, apoiado por uma equipe de agentes de IA, entrega o impacto que antes exigia um time inteiro. |



 ### 4.3 Prompts reutilizáveis para revisão futura

1. "Resuma os 3 pontos mais importantes das fontes sobre [tema], em tópicos."

2. "Crie 5 perguntas de revisão sobre [tema], baseadas apenas nas fontes carregadas."

3. "Compare as fontes entre si: onde elas concordam e onde divergem sobre [tema]?"

4. "Explique [conceito] de forma didática, com um exemplo prático aplicado ao
   setor financeiro."

5. "Com base nas fontes, quais competências técnicas e comportamentais ganham
   mais relevância nesse cenário, e por quê?"

6. "De que forma um profissional da área pode usar IA generativa no dia a dia
   para ser mais produtivo e continuar aprendendo?"


---

## 🛠️ Como este projeto foi construído

1. Definição do tema e dos objetivos de estudo;
2. Curadoria de fontes abertas sobre o tema;
3. Upload das fontes no [NotebookLM](https://notebooklm.google.com/);
4. Elaboração e teste de prompts estratégicos, com documentação de variações e dificuldades;
5. Consolidação das respostas em um miniguia de estudo (resumo + glossário + prompts reutilizáveis).

---

## 👤 Autor

**Wesley Conrado dos Santos**
Estudante de Sistemas de Informação
