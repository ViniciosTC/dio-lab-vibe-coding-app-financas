# 💸 App de Finanças Pessoais do Vinicios com Vibe Coding

PRD refinado no Copilot web:

```
# PRD - Assistente Financeiro Conversacional

## Visão do Produto

Criar um aplicativo de finanças pessoais baseado em conversação, permitindo que usuários registrem gastos, acompanhem metas financeiras e recebam sugestões de economia por meio de linguagem natural.

O produto deve eliminar a necessidade de preencher formulários complexos ou planilhas, tornando o controle financeiro simples, intuitivo e acessível para qualquer pessoa.

## Problema

Muitas pessoas tentam organizar suas finanças, mas abandonam o processo por alguns motivos:

- Excesso de preenchimento manual.
- Interfaces complexas.
- Falta de personalização.
- Pouco engajamento após o cadastro inicial.

Como consequência, os usuários perdem visibilidade sobre seus gastos e têm dificuldade para atingir objetivos financeiros.

## Objetivo

Permitir que qualquer usuário registre suas movimentações financeiras simplesmente conversando com o aplicativo.

Exemplo:

"Comprei um café por R$ 8,50."

O sistema deve interpretar automaticamente:

- Tipo: Despesa
- Valor: R$ 8,50
- Categoria: Alimentação
- Descrição: Café

## Público-Alvo

### Primário

Pessoas iniciantes em educação financeira que desejam organizar suas finanças de forma simples.

### Secundário

- Universitários
- Jovens profissionais
- Pessoas que nunca utilizaram aplicativos financeiros
- Usuários que abandonaram planilhas ou apps tradicionais

## Princípios de Produto

### Simplicidade

O aplicativo deve priorizar facilidade de uso acima da quantidade de funcionalidades.

### Conversação Natural

A conversa é a principal interface do produto.

O usuário não deve precisar aprender comandos específicos para registrar uma movimentação.

### Educação Financeira

O produto deve ajudar o usuário a compreender melhor suas finanças sem utilizar linguagem técnica excessiva.

### Design Universal

O produto deverá seguir os princípios de Design Universal, garantindo que a experiência seja acessível, inclusiva e compreensível para o maior número possível de usuários.

A interface deve considerar usuários com diferentes níveis de alfabetização digital, experiências financeiras, idades e necessidades de acessibilidade.

## Requisitos de Design Universal

### Simplicidade e Intuição

- Interface simples e previsível.
- Fluxos curtos e objetivos.
- Baixa curva de aprendizado.
- Linguagem clara e livre de jargões financeiros.

### Legibilidade

- Alto contraste entre texto e fundo.
- Tamanho de fonte confortável.
- Hierarquia visual clara.
- Espaçamento adequado entre elementos.

### Acessibilidade

- Compatibilidade com leitores de tela.
- Suporte à navegação por teclado quando aplicável.
- Não depender exclusivamente de cores para transmitir informações.
- Textos alternativos para elementos visuais.

### Tolerância a Erros

- Possibilidade de editar movimentações.
- Possibilidade de desfazer ações importantes.
- Confirmações para operações críticas.
- Validação de valores atípicos.

Exemplo:

"Você informou uma despesa de R$ 2.000 com café. Deseja confirmar o valor?"

### Inclusão Cognitiva

- Explicações simples para gráficos e indicadores.
- Feedback claro após cada ação.
- Evitar sobrecarga visual.
- Exibir apenas informações relevantes para o contexto atual.

## MVP - Funcionalidades Principais

### 1. Registro de Transações em Linguagem Natural

O usuário poderá registrar receitas e despesas utilizando texto livre.

Exemplos:

- "Recebi meu salário de R$ 3.500."
- "Gastei R$ 120 no supermercado."
- "Paguei R$ 50 de internet."

Requisitos:

- Extração automática de valor.
- Identificação de receita ou despesa.
- Sugestão automática de categoria.
- Possibilidade de edição.

### 2. Classificação Automática

O sistema deverá categorizar transações automaticamente.

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Lazer
- Saúde
- Educação
- Compras
- Receitas
- Outros

### 3. Metas Financeiras

Usuários poderão criar objetivos financeiros.

Exemplos:

- Economizar R$ 5.000 para uma viagem.
- Criar reserva de emergência.
- Comprar um notebook.

Funcionalidades:

- Definição de valor-alvo.
- Valor atual acumulado.
- Percentual de progresso.
- Previsão estimada de conclusão.

### 4. Agente Financeiro

Assistente virtual responsável por gerar insights e recomendações.

Exemplos:

- "Você gastou 20% mais em alimentação neste mês."
- "Se reduzir R$ 10 por dia em delivery, economizará R$ 300 por mês."
- "Sua meta de viagem está 60% concluída."

Regras:

- Linguagem simples.
- Tom educativo.
- Sem julgamentos.
- Recomendações práticas e acionáveis.

### 5. Dashboard e Relatórios

Visualização simplificada dos dados financeiros.

Indicadores:

- Gastos do mês.
- Receitas do mês.
- Saldo atual.
- Categorias com maiores gastos.
- Evolução mensal.

## Telas do MVP

### Tela 1 - Onboarding

Objetivo:

Apresentar o produto e compreender os objetivos financeiros do usuário.

Itens:

- Nome
- Objetivo financeiro principal
- Meta inicial

### Tela 2 - Chat Financeiro

Tela principal do aplicativo.

Funcionalidades:

- Campo de mensagem.
- Histórico de conversa.
- Sugestões rápidas.
- Registro automático de transações.

### Tela 3 - Dashboard

Exibir:

- Saldo atual.
- Receitas.
- Despesas.
- Gráficos simples.
- Resumo mensal.

### Tela 4 - Metas

Exibir:

- Lista de metas.
- Valor acumulado.
- Percentual atingido.
- Previsão de conclusão.

### Tela 5 - Perfil

Itens:

- Categorias personalizadas.
- Preferências de notificações.
- Dados da conta.

## Fluxo Principal do Usuário

1. O usuário realiza o onboarding.
2. Define uma meta financeira inicial.
3. Registra receitas e despesas via conversa.
4. O sistema interpreta e classifica as movimentações.
5. O dashboard é atualizado automaticamente.
6. O Agente Financeiro gera insights personalizados.
7. O usuário acompanha sua evolução e suas metas.

## Métricas de Sucesso

### Produto

- Número de transações registradas por usuário.
- Usuários ativos semanalmente.
- Taxa de retenção em 30 dias.
- Quantidade de metas criadas.

### Experiência

- Tempo para registrar uma despesa.
- Taxa de acerto da classificação automática.
- Satisfação do usuário.
- Percentual de usuários que registram uma transação no primeiro dia.

### Acessibilidade e Design Universal

- Um novo usuário deve registrar uma despesa em menos de 1 minuto.
- Não deve ser necessário treinamento prévio.
- Usuários devem compreender saldo, gastos e metas sem conhecimento financeiro avançado.
- Todos os fluxos principais devem ser utilizáveis em dispositivos móveis.

## Hipóteses de Validação

Hipótese 1:

Usuários preferem registrar gastos por conversa em vez de preencher formulários.

Hipótese 2:

Sugestões personalizadas aumentam o engajamento.

Hipótese 3:

A simplicidade da experiência reduz a taxa de abandono.

Hipótese 4:

Uma interface baseada em Design Universal aumenta a adoção entre usuários iniciantes.

## Escopo Futuro

- Open Finance.
- Integração bancária.
- Registro por voz.
- Leitura de recibos por foto.
- Previsão de gastos com IA.
- Gamificação.
- Integração com WhatsApp.
- Planejamento financeiro automático.

## Fora do Escopo do MVP

- Investimentos.
- Controle patrimonial.
- Integrações bancárias completas.
- Cartões de crédito integrados.
- Gestão financeira para empresas.
- Contas compartilhadas e múltiplos usuários.

## Critério de Sucesso do MVP

O MVP será considerado validado caso os usuários consigam registrar suas movimentações financeiras exclusivamente por conversação, compreendam sua situação financeira sem treinamento prévio e demonstrem intenção de continuar utilizando o produto após as primeiras semanas de uso.

O sucesso do produto será medido principalmente pela simplicidade da experiência e não pela quantidade de funcionalidades disponíveis.
```
Interações com o Lovable:

> Crie um app de finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

Resultado Final no Lovable: https://meu-dinheiro-em-equilibrio.lovable.app/

<img width="1875" height="966" alt="image" src="https://github.com/user-attachments/assets/d3d4b450-f87e-45d0-aa47-bd0be2b01247" />

Conta Clara

Conta Clara é um assistente financeiro conversacional que ajuda as pessoas a organizarem suas finanças de forma simples e natural.

Em vez de preencher planilhas ou formulários, o usuário conversa com a plataforma utilizando linguagem natural para registrar receitas, despesas e acompanhar objetivos financeiros.
O Problema

Muitas pessoas abandonam o controle financeiro porque os aplicativos tradicionais exigem preenchimento manual, possuem interfaces complexas e apresentam conceitos financeiros difíceis de compreender.

O Conta Clara foi criado para tornar a organização financeira acessível para qualquer pessoa, incluindo usuários iniciantes.
Como Funciona

O usuário registra movimentações financeiras escrevendo mensagens simples como:

Comprei um café por R$ 8,50
Recebi meu salário de R$ 3.500
Gastei R$ 120 no supermercado

A plataforma interpreta automaticamente a informação e identifica:

    Tipo da transação
    Valor
    Categoria
    Descrição

Funcionalidades
Registro Financeiro por Conversa

Permite cadastrar receitas e despesas utilizando linguagem natural, sem formulários ou processos complexos.
Classificação Automática

Organiza automaticamente as movimentações em categorias como:

    Alimentação
    Transporte
    Moradia
    Saúde
    Educação
    Lazer
    Compras
    Receitas

Dashboard Financeiro

Visualização simplificada com informações importantes:

    Saldo atual
    Receitas do mês
    Despesas do mês
    Evolução financeira
    Resumo por categorias

Metas Financeiras

Permite criar e acompanhar objetivos financeiros, como:

    Reserva de emergência
    Viagens
    Aquisição de bens
    Projetos pessoais

Assistente Financeiro

Fornece recomendações personalizadas com foco em educação financeira:

    Alertas de gastos
    Sugestões de economia
    Acompanhamento de metas
    Insights financeiros

Design Universal

O Conta Clara foi projetado seguindo princípios de Design Universal para oferecer uma experiência acessível ao maior número possível de pessoas.

Princípios adotados:

    Interface simples e intuitiva
    Linguagem clara e acessível
    Baixa curva de aprendizado
    Alto contraste visual
    Navegação consistente
    Compatibilidade com recursos de acessibilidade
    Experiência otimizada para dispositivos móveis

Público-Alvo

    Pessoas iniciantes em educação financeira
    Usuários que não gostam de planilhas
    Pessoas que desejam controlar gastos com praticidade
    Usuários que buscam uma experiência mais humana e conversacional

Diferenciais

    Conversação como interface principal
    Registro financeiro sem formulários
    Organização automática de transações
    Recomendações personalizadas
    Foco em simplicidade e acessibilidade
    Experiência construída com princípios de Design Universal

Objetivo
Permitir que qualquer pessoa organize sua vida financeira através de uma conversa simples, natural e acessível.

##Reflexão

### O que funcionou bem?
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 1 interação

### o que não funcionou como o esperado?
Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender masi sobre Vibe Coding

### o que aprendeu sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa, quanto mais detalhes e claresa você dá melhor é a interação
