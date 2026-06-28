# 🧠 Guia Inteligente de Psicologia Histórico-Cultural

![Capa do Projeto](assets/capa.png)

## 📖 Sobre o projeto

Este projeto foi desenvolvido como parte do desafio **"Criando um Caderno Temático com NotebookLM"** da DIO.

O objetivo foi construir uma base de conhecimento especializada sobre **Psicologia Histórico-Cultural**, utilizando o NotebookLM como ferramenta de aprendizagem ativa. Para isso, foi realizada uma curadoria de fontes acadêmicas e normativas que permitem compreender os fundamentos teóricos da abordagem, suas aplicações clínicas e os princípios éticos que orientam a atuação profissional do psicólogo.

Diferentemente de um chatbot genérico, este NotebookLM foi configurado para responder utilizando exclusivamente as fontes selecionadas, permitindo consultas fundamentadas, resumos, comparações entre autores, geração de materiais de estudo e apoio à revisão de conteúdos acadêmicos.

## 📷 Visão Geral do NotebookLM

A imagem abaixo apresenta a interface inicial do NotebookLM desenvolvido para este projeto, contendo as fontes utilizadas e o ambiente de interação com a IA.

![Tela inicial do NotebookLM](assets/notebook-inicial.png)

---

## 🎯 Objetivos

Este caderno temático foi desenvolvido com os seguintes objetivos:

* Consolidar conhecimentos sobre a Psicologia Histórico-Cultural;
* Centralizar referências acadêmicas em um único ambiente de consulta;
* Explorar o potencial do NotebookLM como ferramenta de aprendizagem baseada em documentos;
* Produzir resumos e materiais de revisão apoiados por Inteligência Artificial;
* Avaliar a qualidade das respostas geradas a partir de diferentes estratégias de prompting;
* Desenvolver um material reutilizável para estudos futuros e apoio à prática acadêmica.

---

## 🛠️ Tecnologias Utilizadas

* NotebookLM
* Inteligência Artificial Generativa (Google Gemini)
* GitHub
* Markdown

---

# 📚 Curadoria das Fontes

A qualidade das respostas geradas pelo NotebookLM depende diretamente da qualidade das fontes utilizadas. Por esse motivo, foi realizada uma curadoria com o objetivo de reunir materiais complementares, contemplando fundamentos teóricos, aplicações clínicas e princípios éticos da atuação profissional em Psicologia.

As fontes foram selecionadas para que o modelo fosse capaz de responder tanto questões conceituais quanto perguntas relacionadas à prática clínica da Psicologia Histórico-Cultural.

| Fonte                                                                                                                                                 | Finalidade                                                                                                                                                          |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **LIMA, Ana Ignez Belém; OLIVEIRA NETO, José da Silva (2025). *A práxis na psicologia histórico-cultural: discutindo casos.***                        | Principal referência para aplicações clínicas da Psicologia Histórico-Cultural, reunindo estudos de caso, intervenções e exemplos práticos da atuação do psicólogo. |
| **SANTOS, Gustavo Rezende dos; AQUINO, Orlando Fernández (2014). *A psicologia histórico-cultural: conceitos principais e metodologia de pesquisa.*** | Fundamentação conceitual da abordagem, utilizada para definição dos principais conceitos e da metodologia da Psicologia Histórico-Cultural.                         |
| **CLARINDO, Janailson Monteiro (2020). *Clínica Histórico-Cultural: caracterizando um método de atuação em psicoterapia.***                           | Referência aprofundada sobre os princípios da clínica histórico-cultural e comparação com outras abordagens psicoterápicas.                                         |
| **BOCK, Ana Mercês Bahia; FURTADO, Odair; TEIXEIRA, Maria de Lourdes Trassi (2001). *Psicologias: Uma Introdução ao Estudo de Psicologia.***          | Material introdutório utilizado para contextualizar a Psicologia Histórico-Cultural entre as principais correntes da Psicologia.                                    |
| **Conselho Federal de Psicologia. *Código de Ética Profissional do Psicólogo.***                                                                      | Documento normativo utilizado para orientar respostas relacionadas aos princípios éticos da atuação profissional.                                                   |

## 🎯 Critérios de Seleção

A composição da base de conhecimento buscou contemplar diferentes níveis de aprofundamento.

Enquanto alguns documentos fornecem uma visão introdutória da Psicologia Histórico-Cultural, outros apresentam discussões teóricas mais aprofundadas e aplicações clínicas concretas. A inclusão do Código de Ética Profissional do Psicólogo garante que respostas relacionadas à prática profissional permaneçam alinhadas às normas éticas vigentes.

Essa combinação permite que o NotebookLM funcione como um ambiente de consulta especializado, capaz de integrar conceitos, comparar autores, produzir resumos e apoiar estudos de maneira fundamentada nas referências selecionadas.

---

# 💬 Engenharia de Prompts

Um dos objetivos deste projeto foi explorar diferentes estratégias de interação com o NotebookLM para compreender como a formulação dos prompts influencia a qualidade das respostas geradas.

Durante os testes, observou-se que perguntas muito amplas tendiam a produzir respostas mais genéricas, enquanto prompts específicos e contextualizados resultavam em respostas mais completas, melhor estruturadas e com maior fidelidade às fontes utilizadas.

## Estratégias utilizadas

| Objetivo                       | Exemplo de Prompt                                                                       | Resultado observado                                                                                           |
| ------------------------------ | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| Compreender conceitos          | *Explique o conceito de mediação segundo a Psicologia Histórico-Cultural.*              | Resposta objetiva, fundamentada nas referências e acompanhada de citações das fontes.                         |
| Comparar autores               | *Compare as contribuições de Vigotski e Leontiev para a Psicologia Histórico-Cultural.* | Boa integração entre documentos distintos, permitindo identificar aproximações e diferenças entre os autores. |
| Aplicação clínica              | *Como os princípios da Psicologia Histórico-Cultural podem orientar a prática clínica?* | Respostas fundamentadas principalmente nas obras voltadas à clínica e à práxis profissional.                  |
| Produção de material de estudo | *Elabore um resumo estruturado sobre os principais conceitos da abordagem.*             | Geração de conteúdo organizado, útil para revisão acadêmica.                                                  |
| Autoavaliação                  | *Crie dez questões de revisão sobre os conceitos presentes nas fontes.*                 | Produção de perguntas relevantes para fixação do conteúdo estudado.                                           |

## Aprendizados

Ao longo da utilização da ferramenta, algumas boas práticas ficaram evidentes:

* Especificar o contexto da pergunta melhora significativamente a qualidade das respostas.
* Solicitar comparações entre conceitos ou autores favorece respostas mais analíticas.
* Pedir que o NotebookLM utilize exclusivamente as fontes carregadas aumenta a confiabilidade das informações.
* Solicitar citações das referências facilita a conferência das informações apresentadas.

## Limitações observadas

Durante os testes também foram identificadas algumas limitações:

* Perguntas excessivamente genéricas produzem respostas mais superficiais.
* Temas não contemplados pelas fontes não são desenvolvidos em profundidade, evidenciando a dependência da base documental.
* Em questões muito amplas, a divisão do problema em perguntas menores tende a produzir respostas mais completas e organizadas.

---

# 🧪 Testes Realizados

Após a construção do caderno temático, foram realizados testes com diferentes tipos de perguntas para avaliar a consistência das respostas geradas pelo NotebookLM.

| Categoria                       | Objetivo                                                                                             | Resultado                                                                                              |
| ------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| Conceitos fundamentais          | Verificar a definição de conceitos como mediação, internalização e Zona de Desenvolvimento Proximal. | As respostas apresentaram boa fundamentação teórica e citaram corretamente as fontes utilizadas.       |
| Comparação entre autores        | Avaliar a capacidade do NotebookLM de integrar diferentes documentos.                                | O modelo apresentou respostas consistentes ao comparar autores e conceitos relacionados.               |
| Aplicação clínica               | Investigar a utilização dos princípios da Psicologia Histórico-Cultural em contextos clínicos.       | As respostas utilizaram adequadamente os materiais voltados à prática clínica e à práxis profissional. |
| Aspectos éticos                 | Verificar o uso do Código de Ética Profissional do Psicólogo.                                        | As respostas permaneceram alinhadas aos princípios éticos presentes na documentação utilizada.         |
| Produção de materiais de estudo | Solicitar resumos, questões de revisão e sínteses.                                                   | O NotebookLM mostrou-se eficiente como ferramenta de apoio ao estudo e revisão acadêmica.              |

## Avaliação Geral

Os testes indicaram que o NotebookLM apresentou melhor desempenho em perguntas específicas e contextualizadas, especialmente quando envolviam comparação entre conceitos ou aplicação prática dos conhecimentos presentes nas fontes.

A possibilidade de consultar diretamente as referências utilizadas aumentou a confiabilidade das respostas e facilitou a verificação das informações apresentadas.

---

# 📖 Miniguia de Estudos

## Resumo

A Psicologia Histórico-Cultural compreende o desenvolvimento humano como um processo construído historicamente por meio das relações sociais. Nessa perspectiva, funções psicológicas superiores são desenvolvidas a partir da interação do indivíduo com seu contexto cultural, tendo a linguagem, a mediação e a atividade humana como elementos centrais desse processo.

No campo clínico, essa abordagem busca compreender o sofrimento psicológico considerando a história de vida do sujeito, suas relações sociais e as condições concretas de existência, superando explicações centradas exclusivamente no indivíduo.

## Glossário

**Mediação**
Processo pelo qual instrumentos e signos possibilitam o desenvolvimento das funções psicológicas superiores.

**Internalização**
Transformação das relações sociais em processos psicológicos internos.

**Zona de Desenvolvimento Proximal (ZDP)**
Distância entre aquilo que o indivíduo consegue realizar sozinho e aquilo que consegue realizar com auxílio.

**Funções Psicológicas Superiores**
Capacidades cognitivas desenvolvidas historicamente por meio da interação social.

**Atividade**
Categoria central desenvolvida por Leontiev para compreender a relação entre sujeito, necessidades e realidade objetiva.

## Prompts reutilizáveis

* Explique este conceito utilizando exclusivamente as fontes carregadas no NotebookLM.
* Compare dois autores da Psicologia Histórico-Cultural e destaque suas principais contribuições.
* Produza um resumo estruturado sobre este tema.
* Elabore questões de revisão com base nos documentos utilizados.
* Identifique quais fontes sustentam cada resposta apresentada.
* Explique este conceito utilizando exemplos aplicados à prática clínica.
* Elabore um roteiro de estudos baseado exclusivamente nos materiais disponíveis.

---

# 📌 Considerações Finais

A construção deste caderno temático demonstrou o potencial do NotebookLM como ferramenta de aprendizagem ativa e organização do conhecimento. A experiência evidenciou que a qualidade das respostas depende diretamente da seleção das fontes e da elaboração de prompts claros e contextualizados.

Mais do que produzir resumos automaticamente, o NotebookLM mostrou-se um recurso eficiente para apoiar estudos, revisar conteúdos acadêmicos e integrar diferentes referências em um único ambiente de consulta, mantendo a rastreabilidade das informações por meio das citações das fontes utilizadas.
