# Meu Kit de IA — Estudos e Estágios em TI

Desafio de projeto da DIO, adaptado com apoio do ChatGPT em 12/11/2026.

Base: [kit do Bruno Lima / DIO](https://github.com/digitalinnovationone/meu-kit-de-ia). Os modelos originais foram preservados nas pastas 01-prompts, 02-templates, 03-checklists, 04-skills e 05-delegacao-e-automacao.

## Minha Entrega

**Status:** atalhos exercitados com exemplos de teste e planejamento produzido pela IA. A revisão pessoal e os prints da conversa ainda precisam ser acrescentados antes da submissão na DIO. Não há registro de aprovação humana prévia do plano.

### Minha Tarefa Real

Organizar uma semana de estudos de Python, SQL e Git para apoiar minha preparação para estágios em TI. A tarefa delegada é produzir o planejamento, não concluir os estudos. Cinco sessões de 45 minutos são uma hipótese ajustável de disponibilidade.

### Meus Atalhos

Adaptei o comparador de alternativas de 01-prompts/04-comparar-alternativas.md e a estrutura de 02-templates/01-bom-prompt.md.

| Atalho | Parte fixa | Parte variável |
|---|---|---|
| Analisar vaga | Evidências, lacunas e proibição de inventar experiência | Descrição da vaga e conhecimentos informados |
| Preparar estudo | Revisão, prática e conferência com duração definida | Tema, nível e minutos disponíveis |

#### Atalho 1 — Analisar uma vaga

```text
CONTEXTO
Sou estudante em preparação para estágios em TI.
Use somente a descrição da vaga e os conhecimentos que eu informar.

ENTRADAS
Descrição: [cole o texto sem dados pessoais]
Conhecimentos comprovados: [informe o que já praticou]

INSTRUÇÃO
Compare os requisitos com meus conhecimentos.
Separe obrigatórios, diferenciais e pontos não informados.
Cite os trechos que sustentam cada correspondência.
Diferencie conhecimento declarado de domínio demonstrado.
Se faltar evidência, escreva "não informado".
Não invente experiência, salário, prazo ou elegibilidade.

OBJETIVO E FORMATO
Entregue uma tabela: requisito | evidência na vaga |
evidência no perfil | lacuna ou próxima ação.
Finalize com até três prioridades, identificadas como sugestões da IA.
Não envie candidatura nem altere meu currículo.
```

#### Atalho 2 — Preparar uma sessão de estudo

```text
CONTEXTO
Quero praticar uma habilidade para minha preparação em TI.

ENTRADAS
Tema: [informe o tema]
Nível e conhecimentos prévios: [informe seu nível]
Tempo disponível: [informe os minutos]

INSTRUÇÃO
Crie uma sessão com revisão, prática e conferência.
Distribua os minutos sem exceder o tempo disponível.
Inclua exercício pequeno, entrada de exemplo, resultado esperado
e critério objetivo de conclusão.
Não entregue a solução completa antes da minha tentativa.
Sinalize pré-requisitos e simplifique se necessário.

OBJETIVO E FORMATO
Use linguagem simples e tabela de etapa, duração e atividade.
Depois apresente o exercício e como conferir.
Não marque compromissos nem compre cursos.
```

#### Testes e ajustes

**Teste 1 — exemplo fictício, não é vaga aberta.** Entrada: "Python básico obrigatório; SQL é diferencial". Perfil: "Pratiquei variáveis e condicionais em Python; não informei SQL".

Saída produzida pela IA:

| Requisito | Evidência na descrição | Evidência no perfil | Próxima ação |
|---|---|---|---|
| Python básico obrigatório | Python básico obrigatório | Prática declarada de variáveis e condicionais | Demonstrar aplicação com exercício |
| SQL diferencial | SQL é diferencial | Não informado | Iniciar SELECT e WHERE |

Sugestões da IA: demonstrar condicionais, praticar listas e iniciar SQL. Conferência da IA: requisitos preservados; falta de informação não virou incapacidade; não houve alegação de elegibilidade.

**Teste 2.** Entrada: condicionais em Python; iniciante com variáveis; 45 minutos.

| Etapa | Minutos | Atividade |
|---|---:|---|
| Revisão | 10 | Rever if, elif e else |
| Prática | 25 | Classificar uma nota entre 0 e 10 |
| Conferência | 10 | Testar limites e registrar dúvidas |

Exercício: nota a partir de 7 retorna aprovado; de 5 até abaixo de 7 retorna recuperação; abaixo de 5 retorna reprovado; fora de 0 a 10 retorna nota inválida. Considere somente entradas numéricas nesta sessão.

Casos esperados: -1 → nota inválida; 0 → reprovado; 4,9 → reprovado; 5 → recuperação; 6,9 → recuperação; 7 → aprovado; 10 → aprovado; 11 → nota inválida.

Conferência da IA: 10 + 25 + 10 = 45 minutos; fronteiras incluídas; solução completa não antecipada. O estudante ainda não executou o exercício nesta entrega.

Ajustes incorporados: exigir "não informado" para evitar inferências sobre o perfil; exigir soma de duração e casos de fronteira. Estes são os testes da versão atual, sem alegação de testes de versões anteriores.

### Minha Delegação

Adaptação de 02-templates/03-delegacao.md.

```text
OBJETIVO
Produzir cinco sessões de estudo de Python, SQL e Git
para apoiar minha preparação para estágios em TI.

CONTEXTO
Tenho contato com Python básico. Considere nível iniciante.
Use cinco sessões de 45 minutos como hipótese ajustável,
sem marcar horários e sem vincular o plano a uma vaga real.

RECURSOS
Use os dois atalhos do kit e exemplos fictícios sem dados pessoais.
Não dependa de cursos pagos.

LIMITES
Não invente experiência nem diga que concluí os exercícios.
Não envie mensagens ou candidaturas, não altere agenda,
não faça compras nem crie automações.
A decisão de usar o planejamento é minha.

SUCESSO
Cinco sessões com 10 minutos de revisão, 25 de prática
e 10 de conferência, totalizando 225 minutos.
Cada sessão deve ter tema, exercício, resultado esperado
e critério verificável. Separe fatos, hipóteses e sugestões.

Antes de começar, mostre como pretende realizar essa tarefa.
```

### O Plano da IA

1. Usar a preparação para estágios como contexto.
2. Tratar os cinco períodos de 45 minutos como hipótese ajustável.
3. Distribuir Python em duas sessões, SQL em duas e Git em uma.
4. Definir exercícios pequenos com resultados verificáveis.
5. Conferir durações, pré-requisitos e limites.
6. Entregar o planejamento para revisão pessoal antes do uso.

**Checkpoint:** o plano foi apresentado na conversa antes da produção do resultado. Não houve confirmação humana intermediária; a preparação prosseguiu sob a autorização geral para montar o kit. A revisão pessoal está pendente. Para demonstrar a supervisão do curso, o estudante deve revisar este plano e registrar sua decisão antes de uma nova execução.

**Evidência:** registro textual; o print real da conversa ainda precisa ser acrescentado. Este texto não é uma captura de tela.

### O Resultado

Planejamento produzido pela IA. Cada sessão usa **10 minutos de revisão + 25 de prática + 10 de conferência = 45 minutos**.

| Sessão | Tema | Exercício | Resultado esperado e conferência |
|---|---|---|---|
| 1 | Python: condicionais | Classificar notas de 0 a 10 | Conferir os oito casos do teste do atalho 2 |
| 2 | Python: listas e laços | Contar notas a partir de 7 em 4, 7, 8, 5, 10 | Retornar 3; lista vazia deve retornar 0 |
| 3 | SQL: SELECT e WHERE | Selecionar cursos com carga a partir de 20 horas | Retornar somente Python e SQL nos dados abaixo |
| 4 | SQL: ORDER BY | Ordenar todos os cursos por carga crescente | Git, Python, SQL; cargas 10, 20, 30 |
| 5 | Git: histórico local | Criar anotacoes.txt em pasta de treino, fazer um commit, alterar e fazer outro | Dois commits em git log --oneline e diretório limpo em git status; sem push |

Dados fictícios para as sessões de SQL:

| id | nome | carga_horaria |
|---:|---|---:|
| 1 | Python | 20 |
| 2 | SQL | 30 |
| 3 | Git | 10 |

Pré-requisitos: Python disponível; ambiente SQL com tabela de treino; Git instalado e identidade local configurada. O planejamento não instalou ferramentas nem alterou configurações. Se o preparo consumir a sessão, deve substituir parte da prática, sem ultrapassar 45 minutos; o exercício pode continuar em outra semana.

**Fatos usados:** interesse em estágios e contato com Python básico informados no contexto.

**Hipóteses:** nível iniciante e cinco sessões de 45 minutos.

**Sugestões da IA:** temas, ordem e exercícios.

#### Conferência pela IA

- Cinco vezes 45 = 225 minutos = 3 horas e 45 minutos.
- Cada sessão tem revisão, prática e conferência.
- As notas 7, 8 e 10 atendem ao critério: total 3.
- Carga a partir de 20 retorna Python e SQL; ordem crescente completa: Git, Python, SQL.
- Git prevê dois registros distintos, sem publicação remota.
- O produto entregue é o planejamento, não os exercícios concluídos.
- Nenhuma mensagem, candidatura ou compromisso foi enviado ou alterado.

**Validação pessoal:** pendente. Ainda é necessário conferir disponibilidade e adequação dos temas e acrescentar o print real do resultado antes da submissão.

### Como Foi para Você

O kit deixou preparados dois pedidos reutilizáveis e um planejamento com critérios de conferência. Ainda não há relato pessoal de uso durante a semana. Esse relato será acrescentado após a revisão e a experiência real, sem antecipar ganhos de produtividade.

### Para concluir a entrega

- Revisar o plano e registrar a decisão e os ajustes pessoais.
- Pedir nova execução com o plano revisado para registrar supervisão humana.
- Acrescentar prints reais do plano e do resultado sem dados pessoais.
- Registrar a conferência pessoal e o relato de uso.
- Submeter o link desta cópia pública na DIO.
