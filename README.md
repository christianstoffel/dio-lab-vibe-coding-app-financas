# 💸 App de Finanças Pessoais com Vibe Coding

Prompt final (PRD) refinado no Copilot Web:

```markdown

# Visão do Produto

O Assistente Financeiro Conversacional é um aplicativo de finanças pessoais que permite aos usuários controlar sua vida financeira por meio de conversas em linguagem natural.

O objetivo é eliminar a complexidade presente em aplicativos financeiros tradicionais, tornando a experiência simples, intuitiva e acessível para qualquer pessoa.

O usuário não deve precisar preencher formulários complexos nem navegar por múltiplas telas para registrar movimentações financeiras.

O principal diferencial do produto é que toda a experiência gira em torno de uma conversa com um Agente Financeiro baseado em IA.

Exemplo:

Usuário:
"Gastei R$ 42 no almoço."

Sistema:
"Despesa registrada com sucesso em Alimentação."

# Problema

Muitas pessoas abandonam aplicativos financeiros porque:

- Exigem muito preenchimento manual.
- Possuem interfaces complexas.
- Utilizam linguagem técnica.
- Exigem disciplina constante.
- Não geram valor rapidamente.

O produto deve resolver esses problemas através de uma experiência conversacional simples.

# Público-Alvo

Principal:

- Iniciantes em educação financeira.
- Pessoas que nunca utilizaram apps financeiros.
- Pessoas que desejam maior controle financeiro sem complexidade.

Secundário:

- Universitários.
- Jovens profissionais.
- Trabalhadores autônomos.
- Pessoas que abandonaram outros aplicativos financeiros.
- Usuários com baixa alfabetização digital.

# Princípios Gerais

- Mobile-first.
- Simplicidade acima de tudo.
- Design Universal.
- Baixa carga cognitiva.
- Linguagem simples.
- Experiência conversacional como centro do produto.
- Interface acessível.
- Aprendizagem mínima necessária.

# Proposta de Valor

"Controle suas finanças conversando, não preenchendo planilhas."

# Funcionalidades do MVP

## Registro de Transações via Chat

O usuário deve conseguir registrar receitas e despesas através de mensagens em linguagem natural.

Exemplos:

- Gastei R$ 50 no almoço.
- Recebi R$ 3.500 de salário.
- Paguei R$ 80 de gasolina.
- Ganhei R$ 200 fazendo um freela.

O sistema deve extrair:

- Valor
- Tipo
- Categoria
- Data

E registrar automaticamente a transação.

## Classificação Automática

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Assinaturas
- Receitas
- Outros

Permitir correção manual da categoria.

## Metas Financeiras

Usuário pode criar metas.

Exemplos:

- Guardar R$ 5.000.
- Reserva de emergência.
- Viagem.
- Compra de notebook.

Mostrar evolução automática.

## Agente Financeiro

Gerar orientações financeiras simples.

Exemplos:

- Você gastou mais com alimentação este mês.
- Seu gasto com delivery aumentou.
- Você está próximo de atingir sua meta.

Utilizar tom educativo e não julgador.

## Relatórios

Criar visualizações simples de:

- Gastos por categoria.
- Receitas versus despesas.
- Evolução mensal.
- Evolução das metas.

# Principais Telas

## Tela de Onboarding

Campos:

- Nome
- Faixa de renda
- Objetivo financeiro principal

Ao final, criar primeira meta financeira.

## Tela Principal de Chat

Esta deve ser a tela principal do aplicativo.

Elementos:

- Conversa com o agente financeiro
- Campo de mensagem
- Sugestões rápidas
- Histórico de conversas

## Tela Resumo Financeiro

Mostrar:

- Saldo atual
- Receitas
- Despesas
- Evolução financeira

## Tela de Metas

Mostrar:

- Lista de metas
- Percentual de progresso
- Valor acumulado
- Valor restante

## Tela de Insights

Mostrar:

- Recomendações financeiras
- Alertas
- Oportunidades de economia

# Design Universal

A aplicação deve seguir princípios de Design Universal.

Projetar para que o maior número possível de pessoas consiga utilizar o produto independentemente de idade, experiência tecnológica ou condição física.

Diretrizes:

- Linguagem simples.
- Textos claros.
- Alto contraste.
- Hierarquia visual evidente.
- Poucos elementos por tela.
- Navegação intuitiva.
- Componentes grandes para toque.
- Fluxos curtos.
- Não depender exclusivamente de cores para transmitir significado.

Preparar a interface para futura compatibilidade com leitores de tela.

# Personalidade da IA

O Agente Financeiro deve atuar como:

- Educador financeiro.
- Assistente financeiro pessoal.
- Organizador financeiro.

Características:

- Amigável
- Empático
- Paciente
- Motivador
- Educativo
- Não julgador

Nunca utilizar linguagem que gere culpa ou constrangimento.

Evitar:

"Você gastou dinheiro demais."

Preferir:

"Percebi um aumento nos seus gastos nesta categoria. Posso ajudá-lo a analisar o que aconteceu."

# Regras de Negócio

Toda transação deve possuir:

- Valor
- Tipo
- Categoria
- Data

Valor deve ser maior que zero.

Quando nenhuma categoria for identificada:

- Utilizar categoria "Outros".

Quando nenhuma data for informada:

- Utilizar a data atual.

Saldo:

Saldo = Receitas - Despesas

Ao editar ou excluir transações:

- Recalcular relatórios
- Recalcular metas
- Atualizar insights

Toda meta deve possuir:

- Nome
- Valor alvo

Progresso da meta:

Progresso (%) = Valor acumulado ÷ Valor alvo × 100

Nunca exibir progresso superior a 100%.

# Cenários de Uso

Cenário 1:

Usuário:
"Gastei R$ 45 no mercado."

Resultado:
Registrar despesa automaticamente.

Cenário 2:

Usuário:
"Recebi R$ 2.000 de salário."

Resultado:
Atualizar saldo e receitas.

Cenário 3:

Usuário:
"Quero guardar R$ 5.000 para viajar."

Resultado:
Criar meta financeira.

Cenário 4:

Usuário:
"Quanto eu gastei este mês?"

Resultado:
Apresentar resumo financeiro simples.

# Estilo Visual

Inspirar-se em:

- Nubank
- Cora
- Notion

Características:

- Minimalista
- Moderna
- Limpa
- Profissional
- Amigável

Paleta de cores deve transmitir:

- Confiança
- Clareza
- Segurança financeira

# Dados de Demonstração

Criar automaticamente dados fictícios para demonstração da experiência.

Criar:

- Transações de exemplo
- Metas de exemplo
- Insights de exemplo

Evitar telas vazias.

# Requisitos Técnicos

- Responsivo
- Mobile-first
- Componentes reutilizáveis
- Arquitetura preparada para crescimento
- Estrutura compatível com futuras integrações de IA
- Estrutura compatível com Open Finance

# Fora do Escopo do MVP

Não implementar:

- Integração bancária
- Open Finance real
- Investimentos
- Cartão de crédito avançado
- Planejamento financeiro avançado
- Contas compartilhadas
- Múltiplos usuários por conta
- Gamificação
- WhatsApp
- Telegram
- Exportação PDF
- Exportação Excel

# Objetivo Final

Entregar um MVP funcional, navegável e visualmente refinado que demonstre a proposta de valor de controlar finanças pessoais através de uma conversa simples com uma IA financeira amigável.
```

Interações com o Lovable:

> Crie um aplicativo mobile-first chamado "Assistente Financeiro Conversacional" com base no seguinte PRD: {PRD}

> Várias conversas (Como o histórico de conversas deve funcionar?)

> Neste navegador (Onde os dados (conversas, transações e metas) devem ser salvos?)

> Existe algum problema com o cálculo do saldo atual? Não parece estar calculando corretamente receitas - despesas.

Resultado final no Lovable: https://conversa-financ.lovable.app

<img width="592" height="957" alt="image" src="https://github.com/user-attachments/assets/175bbfb7-57c6-4cde-b1ea-c593c26c72a8" />

<img width="566" height="965" alt="image" src="https://github.com/user-attachments/assets/0ab43e68-bfed-483e-bea5-d70bf5839a7c" />

<img width="557" height="963" alt="image" src="https://github.com/user-attachments/assets/88ef672c-abe9-42bf-8082-111d42c2f88c" />

# Assistente Financeiro Conversacional

Aplicativo de finanças pessoais baseado em IA que permite registrar receitas, despesas e metas financeiras por meio de conversas em linguagem natural.

A proposta do produto é simplificar o controle financeiro para iniciantes, eliminando formulários complexos e reduzindo a necessidade de entrada manual de dados.

## Visão Geral

O Assistente Financeiro Conversacional transforma mensagens simples em ações financeiras.

Em vez de preencher campos manualmente, o usuário apenas descreve o que aconteceu:

```text
"Paguei R$ 200 de gasolina"
```

A assistente interpreta a intenção da mensagem, registra a transação, classifica a categoria e atualiza automaticamente os indicadores financeiros.

## Principais Funcionalidades

### Conversa com IA

A aplicação utiliza uma assistente financeira chamada Lia como principal forma de interação.

Através da conversa, o usuário pode:

- Registrar despesas
- Registrar receitas
- Criar metas financeiras
- Consultar saldo
- Solicitar resumos financeiros
- Receber orientações e insights

### Registro Inteligente de Transações

Interpreta mensagens em linguagem natural e extrai automaticamente:

- Valor
- Tipo da movimentação
- Categoria
- Data

Exemplo:

```text
Paguei R$ 200 de gasolina
```

Resultado:

```text
Despesa registrada
Categoria: Transporte
Valor: R$ 200,00
```

### Classificação Automática

As transações são categorizadas automaticamente em grupos como:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Assinaturas
- Outros

### Dashboard Financeiro

Tela de resumo financeiro contendo:

- Saldo acumulado
- Receitas totais
- Despesas totais
- Resultado do mês
- Evolução do saldo ao longo do tempo

O usuário consegue visualizar sua situação financeira de forma clara e rápida.

### Metas Financeiras

Permite criar e acompanhar objetivos financeiros.

Exemplos:

- Reserva de emergência
- Viagem
- Compra de notebook
- Troca de veículo

Cada meta apresenta:

- Valor objetivo
- Valor acumulado
- Valor restante
- Percentual de progresso

### Gestão de Metas

Recursos disponíveis:

- Criar metas
- Acompanhar evolução
- Adicionar valores às metas
- Excluir metas
- Visualizar progresso consolidado

### Relatórios e Indicadores

O sistema organiza automaticamente os dados financeiros para fornecer:

- Gastos por categoria
- Receitas versus despesas
- Evolução patrimonial
- Acompanhamento de metas

### Dicas e Insights

Área dedicada a recomendações geradas pela IA.

Exemplos:

- Identificação de aumento

## Reflexão

### O que funcionou bem?
O refinamento do PRD feito no Copilot ajudou bastante, pois ao saber que ele seria usado no Lovable, o próprio Copilot foi dando diversas sugestões de melhorias e direcionamentos, de forma que a solicitação fosse mais eficiente e exigisse menos interações.

### O que não funcionou como o esperado?  
Ocorreu uma pequena confusão em relação à exibição dos saldos. Apesar do cálculo estar correto, não ficava claro que, na verdade, o saldo considerava todas as movimentações, enquanto que logo abaixo eram mostradas apenas entradas e saídas do mês. Uma única interação foi suficiente para corrigir o problema e mostrar os dados de forma mais clara. 

### O que aprendeu sobre conversar com IAs?
Aprendi que podemos usar linguagem natural, como uma conversa com outra pessoa. Da mesma forma, quanto mais detalhadas e claras as informações e questionamentos, melhor será a qualidade das respostas e artefatos de saída.
