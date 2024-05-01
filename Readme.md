[![Ada Hack!](readme/AdaHack.png)](https://github.com/Ada-Empregabilidade/adahack-2024-dados/tree/main/Entregas/DD-08)

<h1 align="center">InclusiData Alchemy</h1>
<h3 align="center">Diversidade e Inclusão: Soluções para um Ambiente de Trabalho Equitativo</h3>

---

<h4 align="center"> Projeto idealizado e desenvolvido por: </h4>
<h5 align="center"> Jhenyffer Oliveira • Lisnane Oliveira • Rodrigo Udenal • Victor Lemos</h5>

---

## Sumário
- 🌐 [Quem somos?](#quem-somos) 
- 💼 [Proposta](#proposta) 
- 🔬 [Análise Profunda](#análise-profunda)
- 🔎 [Hipóteses e Validação das Hipóteses](#hipóteses-e-validação-das-hipóteses) 
  - 🗃️ [1. Qual é a qualidade e a diversidade dos dados?](#1-qual-é-a-qualidade-e-a-diversidade-dos-dados) 
  - 📝 [2. Como os indicadores de diversidade aparecem na coleta de dados?](#2-como-os-indicadores-de-diversidade-aparecem-na-coleta-de-dados) 
  - 👥 [3. Como está a presença de diferentes grupos demográficos em cargos de liderança?](#3-como-está-a-presença-de-diferentes-grupos-demográficos-em-cargos-de-liderança) 
- 💡 [Propostas de Soluções](#propostas-de-soluções) 
  - 📈 [Análise da Questão 1](#análise-da-questão-1) 
  - 📋 [Análise da Questão 2](#análise-da-questão-2) 
  - 📊 [Análise da Questão 3](#análise-da-questão-3) 
  - 🌟 [Proposta de Solução Extra](#proposta-de-solução-extra) 
- 🤝 [Organização do Grupo](#organização-do-grupo) 
- 🛠️ [Ferramentas utilizadas](#ferramentas-utilizadas) 

💻 [BÔNUS: clique aqui e veja o código completo com o tratamento dos dados e plotagens](https://github.com/JhenyfferOliveira/Hackaton-ADAHACK/blob/main/DD-08/codigo.ipynb)

---

<h1 id="quem-somos">🌐 Quem somos?</h1>


A **InclusiData Alchemy** se dedica a trazer soluções inovadoras para promover a diversidade e inclusão nas organizações.

Transformamos dados em insights e estratégias.  Utilizando análise de dados, indentificamos lacunas, tendências, oportunidades e orientamos empresas rumo a ambientes mais inclusivos e diversos.

---

<h1 id="proposta"> 💼 Proposta </h1>

Diante da necessidade de promover a **diversidade** e a **inclusão** em seu ambiente de trabalho, a **Corp Solutions** convida a **InclusiData Alchemy** para desenvolver soluções que atendam essa necessidade.

Assim, abordaremos os principais obstáculos identificados nos dados fornecidos pela empresa e traremos propostas de soluções para a promoção de uma mudança cultural que valorize a diversidade e a inclusão na organização.

--- 

<h1 id="análise-profunda"> 🔬 Análise Profunda </h1>

Investimos tempo e esforço para observar minuciosamente os dados fornecidos pela Corp Solutions e levantar hipóteses. Essa fase foi crucial para compreender a situação atual e estabelecer uma base sólida para a tomada de decisão.

---

<h1 id="hipóteses-e-validação-das-hipóteses"> 🔎 Hipóteses e Validação das Hipóteses </h1>

Com algumas visualizações e após muita pesquisa, elaboramos 3 hipóteses que podem evidenciar prováveis razões pelas quais diversidade e inclusão ainda são um desafio para a Corp Solutions.

<h2 id="1-qual-é-a-qualidade-e-a-diversidade-dos-dados"> 🗃️ 1. Qual é a qualidade e a diversidade dos dados? </h2>

Ao tratar os dados, observamos pouca qualidade e baixa diversidade nos dados recebidos. 

Os principais indicadores de diversidade dividem-se em 4 pilares: gênero, etnia, escolaridade e idade. Cada um desses indicadores, contém problemáticas, descritas abaixo.


## • Gêneros:

![distribuição_demográfica_por_gênero](graficos/distribuição_demográfica_por_gênero.png)![distribuição_de_colaboradores_por_etnia_e_gênero](graficos/distribuição_de_colaboradores_por_etnia_e_gênero.png)

**Baixa quantidade de mulheres diversas na empresa.**

![distribuição_por_gênero_entre_diretores](graficos/distribuição_por_gênero_entre_diretores.png)

**Baixa representação de mulheres nos cargos de liderança.**


## • Etnias:

![colaboradores_por_etnia](graficos/colaboradores_por_etnia.png)

**Pouca contratação de grupos étnicos minoritários (pessoas pretas, indígenas e amarelas).**

**Observamos que de acordo com o censo do IBGE de 2022  a população do Brasil é composta por 43,72% de pessoas brancas, 10,23% pretas, 45,62% pardas, 0,42% amarelas e 0,61% indígenas.**


![distribuição_de_colaboradores_por_etnia_(gerente)](graficos/distribuição_de_colaboradores_por_etnia_(gerente).png)![distribuição_de_colaboradores_por_etnia_(diretor)](graficos/distribuição_de_colaboradores_por_etnia_(diretor).png)

**Baixa concentração de grupos étnicos minoritários em cargos de liderança.**


## • Escolaridade:
![número_de_colaboradores_por_senioridade_e_formação](graficos/número_de_colaboradores_por_senioridade_e_formação.png)

**Graduação é um pré-requisito comum de contratação.**

![relação_entre_etnia_e_formação](graficos/relação_entre_etnia_e_formação.png)

**A maioria dos funcionários com perfil étnico-racial minoritário possuem formação superior.**


## • Idades:

![distribuição_de_idade](graficos/distribuição_de_idade.png)

**As contratações se concentram em pessoas mais jovens.**

![visualização_dos_clusters_com_valores_reais](graficos/visualização_dos_clusters_com_valores_reais.png)

**A taxa de retenção é baixa, por volta de 5 anos.**

Com base nessas visualizações, conclui-se que há pouca contratação de grupos étnicos minoritários (mulheres, pessoas pretas, indígenas e amarelas).

No entanto, para as categorias branco e pardo, nota-se conformidade com a autodeclaração da população brasileira. É importante pontuar que, de acordo com o censo do IBGE de 2022, a população do Brasil possui 43,72% de pessoas autodeclaradas brancas e 45,62% autodeclaradas pardas.

Além disso, vale ressaltar que há 10,23% autodeclaradas pretas, 0,42% amarelas e 0,61% indígenas.  

Nesse momento, encontra-se a necessidade da inclusão de mais perfis de grupos subrepresentados, como mulheres, LGBTQIAPN+, gêneros além da cisgeneridade binária, PCD's, etc.

---

<h2 id="2-como-os-indicadores-de-diversidade-aparecem-na-coleta-de-dados"> 📝 2. Como os indicadores de diversidade aparecem na coleta de dados? </h2>

Atualmente, a empresa trabalha com poucos dados de diversidade, apenas etnia e gênero, sendo o último apenas binário, sem abranger os demais.

![distribuição_de_gênero_por_departamento](graficos/distribuição_de_gênero_por_departamento.png)

**Distribuição de gênero por departamento demonstra pouca presença feminina.**

Em relação ao cuidado com os dados sensíveis (ex.: nome, idade, cargo), ficou evidente que a empresa não possui uma solução. Para trabalharmos os dados com segurança, incluímos uma coluna de ID hexadecimais de quatro dígitos e removemos a coluna de nomes e endereços.

![tabela_ids](graficos/tabela_ids.jpg)

**Tabela contendo ID no lugar do nome.**

---

<h2 id="3-como-está-a-presença-de-diferentes-grupos-demográficos-em-cargos-de-liderança"> 👥 3. Como está a presença de diferentes grupos demográficos em cargos de liderança? </h2>

De acordo com os gráficos apresentados na questão 1, é possível observar que apenas 12,4% das mulheres ocupam cargos de diretoria e 24,4% ocupam cargos de gerência.

Em relação a etnia, as pessoas pretas, amarelas e indígenas ocupam menos de 6% dos cargos de diretoria e 9% dos cargos de gerência.

De acordo com as análises realizadas, há disparidades significativas na reoresentação de grupos minoritários em comparação com os grupos majoritários. As mulheres, por exemplo, ocupam cerca de 20% do quadro de colaboradores da empresa. Já a proporção de colaboradores pretos, indígenas e amarelos é 10%.

---

<h1 id="propostas-de-soluções">💡 Propostas de Soluções </h1>

Por fim, com base nas informações que reunimos durante as etapas anteriores e dados colhidos externamente, como os do IBGE, desenvolvemos 4 propostas de solução. 

Essas soluções foram projetadas especificamente para abordar os desafios de diversidade e inclusão identificados na empresa, fornecendo assim um caminho claro e acionável para promover a equidade e a inclusão.

---

<h2 id="análise-da-questão-1"> 📈 Análise da Questão 1 </h2>

**Como proposta de solução, para resolver as problemáticas levantadas na primeira pergunta, sugerimos a implementação de 3 ações conjuntas:**

## • Clube de Benefícios 
Implementação de um programa de mentoria reversa, na qual funcionários de grupos minoritários são emparelhados com funcionários de grupos majoritários para troca de experiências e aprendizado mútuo. 

## • Criação de grupos de afinidade:
Criação de espaços para que os colaboradores compartilhem experiências e perspectivas únicas associadas ao desafio da diversidade no ambiente de trabalho. Promover o desenvolvimento de habilidades de liderança, empatia, comunicação e trabalho em equipe 

## • Promoção de Palestras
Investimento em palestras e outras formas de educação nas empresas acerca de gênero, sexualidade etc.

**Com essas ações, os benefícios esperados são:**

+ Fomento da compreensão e empatia entre funcionários de diferentes origens.
+ Desenvolvimento de uma liderança diversificada e inclusiva.
+ Aumento da retenção de talentos diversificados.
+ Estímulo à inovação e criatividade dentro da empresa.

---

<h2 id="análise-da-questão-2"> 📋 Análise da Questão 2 </h2>

**Como proposta de solução, para resolver as problemáticas levantadas na segunda pergunta, sugerimos a implementação de 3 ações conjuntas:**


## • Coleta de Dados Aprimorada
Implementar formulários mais abrangentes para coleta de dados demográficos, incluindo sexualidade, identidades de gênero não-binárias e deficiências. 

A InclusiData Alchemy fez uma proposta de [formulário](https://forms.gle/TmiCJoefwcU6oXEG8) visando mapear mais características de diversidade.

![FormularioDiversidade](graficos/FormularioDiversidade.png)

**Exemplo de formulário com perguntas aprimoradas.**

## • Melhoria na Visualização de Dados
Aprimorar a plotagem de gráficos para uma visualização mais detalhada e abrangente dos dados de diversidade.

## • Análise de Tendências e Avaliação de Impacto
Realizar análises mais profundas sobre as tendências ao longo do tempo e avaliar o impacto das medidas de diversidade e inclusão implementadas.

## • Integração com Processos de Tomada de Decisão
Garantir que os dados de diversidade coletados sejam considerados integralmente nos processos de recrutamento e tomada de decisão da empresa.

## • Garantia da Privacidade dos Dados
Utilizar no uma coluna de ID único para identificação ao invés de uma coluna com o nome dos colaboradores no armazenamento dos dados de diversidade.

**Com essas ações, os benefícios esperados são:**

+ Coleta de dados mais abrangente e representativa.
+ Melhoria na compreensão dos padrões de diversidade.
+ Melhor embasamento para tomadas de decisão relacionadas à diversidade e inclusão.
+ Promoção de uma cultura mais inclusiva e equitativa.

---

<h2 id="análise-da-questão-3"> 📊 Análise da Questão 3 </h2>

**Como proposta de solução, para resolver as problemáticas levantadas na terceira pergunta, sugerimos a implementação de 3 ações conjuntas:**

## • Formação Continuada Específica
Desenvolver programas de formação continuada direcionados a grupos minoritários para promover o acesso à educação e desenvolvimento profissional.

## • Progressão de Carreira Equitativa
Implementar políticas e programas que garantam oportunidades equitativas de progressão de carreira para todos os funcionários, independentemente de sua origem étnica.

## • Monitoramento e Avaliação
Realizar monitoramento regular do progresso dos programas de formação e progressão de carreira para garantir sua eficácia e fazer ajustes conforme necessário.

---

<h2 id="proposta-de-solução-extra"> 🌟 Proposta de Solução Extra </h2>

## • Aquisição de Novos Talentos Através de Stands em Eventos de Tecnologia 2024/2025

Anualmente os 30 principais eventos de tecnologia que ocorrem no Brasil recebem cerca de 500 mil participantes o que torna viável a aquisição de parte desses talentos.

Esta ação também aumento o alcance da marca Corp Solutions dentro do ecossistema de empresas brasileiras.

Este levantamento foi realizado dentro de eventos com público plural ou com iniciativas de diversidade e inclusão para o público o que está alinhado com os objetivos de aumento na diversidade. 

**Com essa ação, os benefícios esperados são:**
+ Maior acesso à educação e desenvolvimento profissional para grupos minoritários.
+ Redução das disparidades na progressão de carreira.
+ Promoção da equidade e inclusão dentro da empresa.
+ Contribuição para um ambiente de trabalho mais diversificado e inovador.

---

<h1 id="organização-do-grupo"> 🤝 Organização do Grupo </h1>

Para organização, utilizamos algumas ferramentas:
- Google Drive, para concentração da documentação, imagens, entre outros;
- Documentos Google, para estruturar as etapas de um plano de ação, levantamento de hipóteses, comprovação ou negação das hipóteses, insights, pesquisas de referências externas e o direcionamento da proposta;
- Monday, para dividir tarefas, estabelecer prazos, ajustar notas e comentários sobre as atividades.

#### Entre essas ferramentas, vale destacar o Roteiro criado no Documentos Google, disponível [aqui](https://docs.google.com/document/d/1FiSdodF9yHHHeaZOQbZjmg-30HWEZoJMiIvCgcnEMPA/edit?usp=sharing), e o Monday, disponível abaixo.

![Monday1](readme/Monday1.png)
![Monday1](readme/Monday2.png)
![Monday1](readme/Monday3.png)

---

<h1 id="ferramentas-utilizadas"> 🛠️ Ferramentas utilizadas </h1>

| Python | Pandas | Matplotlib | Seaborn | Folium | Git | Monday |
| ------ | ------ | ---------- | ------- | ------ | --- | ------ |
| <img src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/files/python-logo-only.svg" width="100"> | <img src="https://pandas.pydata.org/static/img/pandas_mark.svg" width="100"> | <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width="110"> | <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" width="130"> | <img src="https://python-visualization.github.io/folium/latest/_images/folium_logo.png" width="60"> | <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.svg" width="140"> | <img src="https://seeklogo.com/images/M/monday-logo-918DBDD43D-seeklogo.com.png" width="150" > |
