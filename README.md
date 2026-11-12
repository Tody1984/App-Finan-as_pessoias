# App-Finan-as_pessoias
Aplicativo de Finanças pessoais desenvolvido com Lovable

Este aplicativo foi desenvolvido como parte de avaliação do curso, Criando um APP de Organização de Finanças Pessoais com Vibe Coding;

PRD Feito no Copilot

# PRD – Aplicativo de Finanças Pessoais Conversacional

## 1. Visão Geral do Produto

### Nome Provisório

Meu Agente Financeiro

### Resumo

Aplicativo de organização financeira pessoal baseado em conversas em linguagem natural.

O usuário registra despesas, receitas, metas e dúvidas financeiras por meio de um chat inteligente, sem a necessidade de preencher planilhas ou formulários complexos.

O sistema interpreta as mensagens, organiza automaticamente as informações financeiras e oferece recomendações personalizadas para auxiliar o usuário a desenvolver hábitos financeiros saudáveis.

### Princípio Fundamental

O produto deve seguir os princípios de Design Universal, garantindo uma experiência compreensível, acessível e intuitiva para o maior número possível de pessoas.

A plataforma deve ser utilizável por:

- Iniciantes em educação financeira
- Pessoas com pouca familiaridade tecnológica
- Jovens e idosos
- Usuários com diferentes capacidades cognitivas
- Pessoas com necessidades de acessibilidade visual e motora

O objetivo é que qualquer pessoa consiga utilizar o aplicativo sem treinamento prévio.

---

## 2. Problema

Grande parte das pessoas abandona aplicativos de controle financeiro porque:

- Exigem cadastro manual excessivo
- Possuem interfaces complexas
- Demandam disciplina constante para atualização
- Utilizam linguagem técnica ou financeira
- Apresentam relatórios difíceis de interpretar

Como consequência, muitos usuários deixam de acompanhar sua situação financeira e têm dificuldade para criar bons hábitos de organização.

---

## 3. Objetivo do Produto

Permitir que qualquer pessoa organize sua vida financeira utilizando uma conversa simples e natural.

### Objetivos de Negócio

- Reduzir a barreira de entrada para novos usuários
- Aumentar frequência de uso
- Incentivar hábitos financeiros saudáveis
- Promover educação financeira de forma simples
- Tornar o controle financeiro mais acessível e inclusivo

---

## 4. Público-Alvo

### Público Primário

Pessoas entre 18 e 45 anos que desejam organizar suas finanças pessoais, mas possuem pouca experiência com planejamento financeiro.

### Público Secundário

- Estudantes
- Jovens profissionais
- Autônomos
- Pessoas retomando a organização financeira
- Usuários que abandonaram aplicativos financeiros tradicionais por complexidade

---

## 5. Proposta de Valor

Controle suas finanças conversando com um assistente financeiro pessoal.

### Diferenciais

- Conversa em linguagem natural
- Classificação automática das movimentações
- Baixo esforço operacional
- Recomendações personalizadas
- Interface inclusiva
- Design Universal
- Experiência amigável para iniciantes

---

## 6. Funcionalidades do MVP

### 6.1 Registro de Transações via Chat

Exemplo:

Gastei R$ 45 no mercado hoje.

Resultado esperado:

- Valor: R$ 45
- Tipo: Despesa
- Categoria: Alimentação
- Data: Hoje

Exemplo:

Recebi R$ 2.500 do salário.

Resultado esperado:

- Receita
- Categoria: Salário
- Valor: R$ 2.500

### 6.2 Classificação Automática

Categorias sugeridas automaticamente:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Salário
- Investimentos
- Outros

O usuário poderá corrigir classificações incorretas.

### 6.3 Metas Financeiras

Exemplo:

Quero guardar R$ 5.000 para uma viagem.

O sistema deverá:

- Registrar a meta
- Mostrar progresso
- Informar quanto falta
- Estimar prazo de conclusão

### 6.4 Agente Financeiro

Responsável por:

- Responder dúvidas
- Sugerir economia
- Identificar padrões de consumo
- Incentivar hábitos positivos
- Traduzir conceitos financeiros complexos em linguagem simples

Exemplo:

Você gastou 20% mais com delivery este mês.

Se economizar cerca de R$ 100 por mês nessa categoria, poderá atingir sua meta mais rapidamente.

### 6.5 Dashboard Simplificado

Apresentar:

- Receitas do mês
- Gastos do mês
- Saldo atual
- Categorias com maior gasto
- Evolução das metas
- Recomendações do Agente Financeiro

---

## 7. Requisitos de Design Universal

### DU01 – Linguagem Simples

Todo conteúdo deve utilizar linguagem clara e acessível.

Evitar:

Sua liquidez mensal encontra-se comprometida.

Preferir:

Você está gastando mais do que o planejado neste mês.

### DU02 – Baixa Carga Cognitiva

O aplicativo deve exigir o menor esforço mental possível.

Diretrizes:

- Poucas opções por tela
- Uma ação principal por vez
- Fluxos curtos
- Navegação intuitiva

### DU03 – Múltiplas Formas de Interação

Permitir:

- Digitação livre
- Sugestões rápidas
- Botões de ação
- Comandos pré-definidos
- Evolução futura para entrada por voz

### DU04 – Acessibilidade Visual

Diretrizes:

- Contraste adequado
- Fontes legíveis
- Hierarquia visual clara
- Elementos clicáveis de tamanho confortável
- Não depender apenas de cores para transmitir significado

### DU05 – Relatórios de Fácil Interpretação

Priorizar:

- Resumos visuais simples
- Indicadores claros
- Explicações em texto

Exemplo:

Você gastou R$ 300 em alimentação este mês.

Isso representa 25% dos seus gastos.

### DU06 – Tolerância a Erros

O sistema deve ajudar o usuário a completar informações ausentes.

Exemplo:

Entrada:

Comprei no mercado.

Resposta:

Entendi. Quanto você gastou?

### DU07 – Inclusão Financeira

O aplicativo deve funcionar adequadamente para usuários que:

- Não investem
- Não utilizam cartão de crédito
- Não possuem conta digital
- Não conhecem conceitos financeiros

### DU08 – Mobile First

Toda experiência principal deve ser projetada inicialmente para dispositivos móveis.

---

## 8. Fluxos do Usuário

### Primeiro Acesso

1. Criar conta
2. Informar objetivo financeiro
3. Receber boas-vindas do Agente Financeiro
4. Registrar primeira movimentação

### Uso Diário

1. Usuário envia mensagem
2. IA interpreta intenção
3. Sistema registra informação
4. Usuário recebe confirmação
5. Dashboard é atualizado automaticamente

---

## 9. Principais Telas

### Tela 1 – Onboarding

Objetivo:

Conhecer o usuário e suas metas.

Elementos:

- Nome
- Objetivo financeiro
- Faixa de renda (opcional)

### Tela 2 – Chat Financeiro

Tela principal.

Elementos:

- Histórico da conversa
- Campo de mensagem
- Sugestões rápidas
- Comandos frequentes

### Tela 3 – Dashboard

Elementos:

- Saldo atual
- Receitas
- Despesas
- Resumo das categorias
- Evolução financeira

### Tela 4 – Metas

Elementos:

- Lista de metas
- Percentual concluído
- Recomendações

### Tela 5 – Perfil e Configurações

Elementos:

- Dados do usuário
- Preferências
- Categorias personalizadas
- Acessibilidade
- Notificações

---

## 10. Requisitos Funcionais

### RF01

Registrar despesas via linguagem natural.

### RF02

Registrar receitas via linguagem natural.

### RF03

Classificar movimentações automaticamente.

### RF04

Permitir edição de registros.

### RF05

Criar metas financeiras.

### RF06

Gerar relatórios simplificados.

### RF07

Oferecer recomendações automáticas.

### RF08

Exibir evolução financeira.

### RF09

Interpretar mensagens incompletas através de diálogo contextual.

### RF10

Explicar informações financeiras em linguagem simples.

---

## 11. Requisitos Não Funcionais

### Performance

- Resposta da IA em até 3 segundos

### Segurança

- Criptografia de dados sensíveis
- Autenticação segura
- Proteção de dados pessoais

### Usabilidade

- Registro de gasto em menos de 15 segundos
- Curva de aprendizado mínima
- Fluxos simples para iniciantes

### Acessibilidade

- Conformidade com boas práticas WCAG
- Alto contraste
- Compatibilidade com leitores de tela
- Navegação assistida

### Escalabilidade

- Estrutura preparada para futura integração bancária

---

## 12. Métricas de Sucesso

### Engajamento

- Pelo menos uma transação registrada por usuário ativo por dia

### Retenção

- Retenção D7 superior a 30%

### Valor Percebido

- 70% dos usuários consideram o aplicativo mais simples que planilhas ou apps tradicionais

### Precisão

- Classificação automática correta em pelo menos 80% dos registros

### Acessibilidade

- 90% dos usuários conseguem registrar uma despesa sem ajuda durante os testes

---

## 13. Hipóteses a Validar

### H1

Usuários preferem registrar movimentações por conversa em vez de formulários.

### H2

Recomendações personalizadas aumentam engajamento.

### H3

Metas financeiras aumentam retenção.

### H4

Design Universal reduz abandono durante o onboarding.

### H5

Linguagem simples aumenta compreensão dos relatórios.

---

## 14. Plano de Validação Inicial

### Fase 1 – Protótipo

Construir no Lovable:

- Onboarding
- Chat Financeiro
- Dashboard
- Metas

Objetivo:

Validar compreensão da proposta.

### Fase 2 – Testes com Usuários

Grupo inicial:

5 a 10 usuários.

Tarefas:

- Registrar gasto
- Registrar receita
- Criar meta
- Consultar relatório

Avaliar:

- Facilidade de uso
- Clareza dos textos
- Tempo de execução
- Feedback geral

### Fase 3 – MVP Funcional

Implementar:

- Banco de dados
- Interpretação por IA
- Dashboard
- Metas financeiras
- Recomendações automáticas

---

## Prompt Estratégico para Lovable

Crie um aplicativo de finanças pessoais baseado em conversação por linguagem natural.

O produto deve seguir rigorosamente os princípios de Design Universal, sendo acessível, intuitivo e utilizável pelo maior número possível de pessoas, incluindo iniciantes em finanças, pessoas com baixa familiaridade tecnológica, idosos e usuários com diferentes necessidades de acessibilidade.

Priorize simplicidade, clareza, linguagem humana, baixa carga cognitiva e experiência mobile-first.

O chat deve ser a funcionalidade principal do produto. Os usuários devem conseguir registrar receitas, despesas, metas e consultar relatórios apenas conversando com o sistema.

Evite interfaces complexas, excesso de gráficos e jargões financeiros. Sempre privilegie compreensão e facilidade de uso.
