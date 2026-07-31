# 💰 Caderno Temático: Educação Financeira Pessoal

> Projeto do Desafio de Projeto DIO — uso do NotebookLM como ferramenta de aprendizagem ativa.

---

## 1. Contexto e Objetivos

**Tema :** Educação financeira pessoal — orçamento, poupança e gestão de dívidas.

Escolhi esse recorte por ser um assunto financeiro introdutório com aplicação direta na vida cotidiana, e por existir farto material aberto e confiável produzido por instituições oficiais brasileiras (Banco Central, Febraban), o que favorece uma curadoria de fontes sólida.

**Objetivos de estudo:**
- Compreender os princípios básicos de planejamento e controle do orçamento pessoal.
- Entender a lógica da poupança e da formação de reserva de emergência.
- Compreender as causas do endividamento e estratégias de organização e renegociação de dívidas.
- Construir um vocabulário técnico consistente sobre finanças pessoais.
- Desenvolver um repertório de prompts reutilizáveis para revisar o assunto no futuro, ou aplicar a mesma metodologia a outros temas.

---

## 2. Curadoria de Fontes

Fontes abertas selecionadas e carregadas no NotebookLM (texto/PDF). Priorizei materiais produzidos por instituições oficiais e reconhecidas em educação financeira no Brasil, evitando conteúdo comercial disfarçado de material educativo.

| # | Fonte | Autor/Instituição | Link | Tipo |
|---|-------|--------------------|------|------|
| 1 | *Caderno de Educação Financeira – Gestão de Finanças Pessoais* | Banco Central do Brasil (Depef) | https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf | PDF oficial |
| 2 | *Estratégia Nacional de Educação Financeira (ENEF)* | Banco Central do Brasil | https://www.bcb.gov.br/pre/pef/port/Estrategia_nacional_Educacao_Financeira_ENEF.pdf | PDF oficial |
| 3 | E-books de educação financeira (orçamento, poupança, dívidas) | Meu Bolso em Dia (Febraban, certificado pelo Banco Central) | https://meubolsoemdia.com.br/e-books | E-books (site) |
| 4 | Publicação dos 10 anos da ENEF (contexto e panorama nacional) | Meu Bolso em Dia / ENEF | https://meubolsoemdia.com.br/ebooks/enef | E-book (PDF) |

> ⚠️ Nota de curadoria: dei preferência a materiais publicados diretamente por órgãos oficiais (bcb.gov.br) ou por plataformas certificadas pelo Banco Central, em vez de e-books comerciais avulsos de terceiros, que variam muito em qualidade e rigor técnico.

---

## 3. Engenharia de Prompts e "Cicatrizes"

Documentação do processo de tentativa e erro: perguntas estratégicas, variações testadas, e dificuldades encontradas para extrair boas respostas da IA.

### 3.1 Perguntas estratégicas testadas

| Prompt testado | Objetivo | Resposta obtida (resumo) | Fontes citadas pela IA | Dificuldades / ajustes feitos |
|---|---|---|---|---|
| "Quais são os passos recomendados para montar um orçamento pessoal, segundo as fontes?" | Extrair um processo prático | Para montar um orçamento pessoal de forma eficaz, as fontes recomendam um método estruturado em quatro etapas principais: planejamento, registro, agrupamento e avaliação
. O objetivo central dessa ferramenta é permitir que o cidadão conheça sua realidade financeira, defina prioridades e equilibre suas contas para alcançar sonhos e projetos
.
Abaixo detalho os passos e as recomendações fundamentais:
1. Etapas para Elaboração do Orçamento
1ª Etapa: Planejamento: Consiste em estimar as receitas e despesas para o período (geralmente um mês ou um ano)
. Deve-se utilizar a rotina passada como base para prever o futuro, diferenciando o que é fixo (salário, aluguel) do que é variável (comissões, conta de luz)
. É crucial incluir compromissos sazonais (IPVA, IPTU, material escolar) e dívidas já assumidas (parcelas de cartão)
.
2ª Etapa: Registro: É o ato de anotar todas as entradas e saídas, preferencialmente de forma diária para evitar esquecimentos
. As fontes sugerem guardar notas fiscais, recibos e conferir regularmente extratos bancários e faturas
.
3ª Etapa: Agrupamento: Para melhor compreensão, os gastos devem ser reunidos por categorias com características similares, como alimentação, habitação, transporte e lazer
. Isso facilita a identificação de onde o dinheiro está sendo gasto e onde cortes podem ser feitos
.
4ª Etapa: Avaliação: É o momento de refletir sobre o comportamento financeiro do mês
. Deve-se verificar se o balanço foi superavitário (sobrou dinheiro), neutro ou deficitário (faltou dinheiro)
Nesta fase, avalia-se a possibilidade de eliminar gastos desnecessários, reduzir supérfluos e aumentar receitas

2. Princípios e Estratégias Fundamentais
Regra de Ouro: O objetivo principal deve ser manter o orçamento superavitário, ou seja, garantir que as despesas sejam inferiores às receitas.

Pague-se Primeiro: Ao atingir um orçamento superavitário, a recomendação é separar uma parte para poupar assim que receber a renda, antes mesmo de pagar as despesas.
Esperar o fim do mês para poupar o que sobrar costuma ser pouco efetivo.

Participação Familiar: Para quem vive em família, o sucesso da gestão depende do comprometimento de todos os membros
. Recomenda-se buscar limites em conjunto e ter projetos comuns, transformando o orçamento em um fator de união familiar.

3. Ferramentas e Recursos
Não existe uma ferramenta única obrigatória; o registro pode ser feito em papel, planilhas eletrônicas ou aplicativos de celular, conforme o conforto do usuário.
O Banco Central também disponibiliza a Calculadora do Cidadão para auxiliar em cálculos financeiros diversos.

As fontes enfatizam que o orçamento não é apenas um registro do passado, mas principalmente um exercício de planejamento futuro que deve ser acompanhado e revisado constantemente.

| "Qual a diferença entre poupança e reserva de emergência?" | Testar se a IA diferencia bem conceitos próximos | Segundo as fontes, a principal diferença entre poupança e reserva de emergência reside na finalidade do dinheiro e na estratégia de uso, embora ambas resultem do ato de economizar.
Aqui estão as distinções detalhadas:
1. Definição e Propósito
Poupança: É definida de forma ampla como a diferença entre as receitas e as despesas, ou seja, o "dinheiro que sobra" após o pagamento das contas
O seu objetivo é variado: pode ser usada para realizar sonhos e projetos (como comprar um carro ou viajar), preparar a aposentadoria ou lidar com imprevistos.

Reserva de Emergência: É uma poupança específica destinada exclusivamente a cobrir imprevistos e eventualidades (como acidentes, problemas de saúde ou reparos urgentes na casa).
Sua função primordial é evitar que o cidadão precise recorrer ao crédito e caia no endividamento em momentos de crise.

2. Características do Investimento
As fontes destacam que a reserva de emergência exige um cuidado especial onde o dinheiro é aplicado:
Liquidez e Risco: Enquanto outros tipos de poupança para projetos de longo prazo podem aceitar riscos maiores em busca de rentabilidade, a reserva de emergência deve ser aplicada em investimentos de alta liquidez e baixo risco.
Isso garante que o recurso esteja disponível imediatamente e sem perdas de valor no momento em que a emergência ocorrer.

Disponibilidade: Diferente de uma poupança para um "sonho" (onde se sabe quando o dinheiro será usado), o dinheiro da reserva deve estar "lá, sem perdas, e disponível de forma rápida".

3. Disciplina de Uso
Não misturar as finalidades: Uma recomendação crucial das fontes é que o cidadão não deve cair na tentação de usar os recursos da reserva de emergência para outros fins, como consumo ou realização de projetos (comprar algo que deseja).

Prevenção: A reserva de emergência funciona como uma "autoproteção" financeira. Se você usa o dinheiro da reserva para comprar um bem, fica vulnerável caso um imprevisto real aconteça enquanto ainda está tentando recompor esse valor.

Em resumo, a poupança é o conceito geral de guardar dinheiro para o futuro, enquanto a reserva de emergência é um "seguro próprio" obrigatório dentro do planejamento financeiro, focado na segurança e na rapidez de acesso para evitar dívidas em momentos críticos.

| "Quais são as causas mais comuns de endividamento apontadas nas fontes, e quais estratégias de renegociação são sugeridas?" | Sintetizar informação de várias fontes | *(preencher)* | *(preencher)* | *(preencher)* |
| "Crie 5 perguntas de revisão sobre os conceitos discutidos nas fontes" | Gerar material de autoavaliação | *(preencher)* | *(preencher)* | *(preencher)* |

### 3.2 Variações de prompt e lições aprendidas

> Espaço para registrar, por exemplo: perguntas muito abertas geraram respostas genéricas; pedir "cite a fonte exata" melhorou a precisão; pedir "responda em formato de checklist prático" mudou o formato de saída, etc.

- **Prompt inicial:** *(descreva)* → **Problema encontrado:** *(ex: resposta genérica, sem citar a fonte)*
- **Prompt ajustado:** *(nova versão)* → **Resultado:** *(o que melhorou)*

### 3.3 Principais dificuldades (troubleshooting)

- *(ex: a IA misturou recomendações de fontes diferentes sem indicar qual dizia o quê)*
- *(ex: respostas muito genéricas — foi preciso pedir exemplos numéricos ou práticos)*
- *(ex: termos técnicos precisaram ser simplificados para o glossário)*

---

## 4. Miniguia de Estudo (Entrega Final)

### 4.1 Resumos estruturados

#### O que é educação financeira pessoal
*(resumo gerado e revisado a partir das fontes — 1 a 2 parágrafos)*

#### Orçamento pessoal e familiar
*(resumo: como montar, categorias de gastos, controle mensal)*

#### Poupança e reserva de emergência
*(resumo: por que poupar, quanto poupar, onde guardar a reserva)*

#### Endividamento: causas e estratégias de saída
*(resumo: principais causas do endividamento no Brasil, renegociação, prevenção)*

### 4.2 Glossário

| Termo | Definição |
|---|---|
| **Orçamento pessoal** | Planejamento das receitas e despesas de um indivíduo ou família em um período. |
| **Reserva de emergência** | Valor guardado para cobrir despesas imprevistas, sem recorrer a crédito. |
| **Endividamento** | Situação em que os compromissos financeiros superam a capacidade de pagamento. |
| **Inadimplência** | Não cumprimento de uma obrigação financeira no prazo combinado. |
| **Renegociação de dívida** | Processo de reformular condições de pagamento de uma dívida existente. |
| **Consumo consciente** | Prática de consumir de forma alinhada ao planejamento financeiro e às reais necessidades. |
| *(adicionar mais termos conforme o estudo avança)* | |

### 4.3 Prompts reutilizáveis para revisão futura

Prompts genéricos, pensados para funcionar com qualquer fonte carregada no NotebookLM sobre este ou outros temas:

1. "Resuma os 3 conceitos mais importantes deste material em linguagem simples, citando a fonte de cada um."
2. "Crie um quiz de 5 perguntas de múltipla escolha sobre este tema, com gabarito."
3. "Explique [conceito X] como se eu não soubesse nada sobre o assunto, depois aprofunde em um segundo parágrafo."
4. "Compare [conceito A] e [conceito B]: em que se parecem, em que diferem, e dê um exemplo prático de cada."
5. "Liste possíveis lacunas ou contradições entre as fontes carregadas sobre este tema."

---

## Como este repositório foi construído

Repositório criado para o Desafio de Projeto da [DIO](https://www.dio.me/), com o objetivo de demonstrar o uso do NotebookLM como ferramenta de aprendizagem ativa, aplicando curadoria de fontes, pensamento crítico sobre as respostas da IA e organização do conhecimento em um material de estudo reutilizável.
