# Anotações: Introdução à Engenharia de Prompts

Este documento reúne minhas anotações ao longo das aulas deste curso.

---

### Módulo 1: Introdução

## Aula 1: Por que aprender Engenharia de Prompts?

**O que aprendi nesta aula:**
Nesta primeira aula do curso, conduzida pela instrutora Elidiana Andrade (Tech Education Analyst na DIO), tivemos uma introdução sobre os motivos pelos quais dominar a Engenharia de Prompts é tão importante hoje em dia, antes mesmo de explorarmos ferramentas e conceitos mais profundos.

A instrutora fez uma analogia excelente que deixou tudo muito claro: **o exemplo da pizzaria**. 
Imagine que você está com fome e manda a seguinte mensagem para a pizzaria: *"Oi, quero uma pizza"*. O atendente vai ter que fazer diversas perguntas (Qual o sabor? Qual o tamanho? É para entregar?), simplesmente porque você não deu detalhes suficientes. 

O mesmo acontece com os modelos de Inteligência Artificial: se você não for claro no seu pedido, a IA ficará perdida e te dará respostas genéricas, vagas ou imprecisas.

**Exemplo Prático: Escrevendo um E-mail**
Se pedirmos para a IA apenas *"Escreva um e-mail para um cliente"*, ela entregará um texto genérico, pois não sabe:
- O motivo do e-mail
- O tom de voz que deve ser utilizado
- O que precisa ser destacado ou qual é a informação essencial

Para que a IA entregue um resultado ideal e útil, o pedido precisa ser **específico**. 

Abaixo, um exemplo de um "bom pedido" (um bom prompt) testado na aula:

```text
Escreva um e-mail formal para um cliente que está interessado em um notebook gamer chamado Acer Nitro V15. 

Destaque as principais características do produto, como:
- Processador interno i5
- Memória RAM 15GB
- SSD 512GB
- Display de 16 polegadas com taxa de atualização de 120Hz
- Teclado RGB personalizável
- Refrigeração avançada

Além disso, ofereça um desconto especial de 10% e inclua um código promocional. O tom deve ser profissional, mas amigável.
```

<br>
<div align="center">
  <em>Exemplo Prático: Prompt no ChatGPT</em><br>
  <a href="./exemplos/modulo-01-aula-01/Output-Email-Acer-Nitro.pdf">
    <img src="./exemplos/modulo-01-aula-01/email-acer-nitro-prompt.png" alt="Exemplo Prático: Prompt no ChatGPT" width="600">
  </a>
  <br>
  <sup>Fonte: Autoral (2026)</sup>
</div>
<br>

**Análise do Teste:**
Com base nesse teste prático, ficou evidente que a qualidade do prompt influencia diretamente a qualidade da resposta do modelo. Quanto mais claros e específicos formos, melhor será o resultado entregue pela IA.

**Definições Importantes:**
- **Prompt:** É a mensagem ou o comando direto que você envia ao Modelo de IA.
- **Engenharia de Prompts:** É a habilidade de formular esses comandos de forma eficaz e inteligente, garantindo que a IA gere exatamente a resposta e o resultado que você realmente precisa.

> [!IMPORTANT]
> **Uma Habilidade para a Vida**
> Saber formular bons prompts não é apenas uma habilidade técnica restrita a programadores. É uma habilidade prática e versátil que pode transformar tanto a vida profissional quanto a pessoal!
> 
> Com ela, podemos:
> - Escrever e-mails e redigir textos muito mais rápido.
> - Obter resumos de documentos longos de maneira eficiente.
> - Gerar ideias criativas para novos projetos.
> 
> Usando a Engenharia de Prompts de maneira inteligente, o principal ganho é conseguir poupar um tempo e um esforço absurdos no dia a dia.

---

## Aula 2: O que você precisa para começar?

**O que aprendi nesta aula:**
Nesta aula, discutimos sobre os pré-requisitos para começar na Engenharia de Prompts. A mensagem principal é que **não é necessário ser um especialista em Inteligência Artificial** para aprender e utilizar essa habilidade no dia a dia.

No entanto, é muito importante ter noções básicas sobre dois pilares que dão base a tudo:
- **Processamento de Linguagem Natural (PLN):** É a área da Inteligência Artificial que trata da interação entre máquinas e a linguagem humana. É essa tecnologia que permite que o computador entenda o texto que escrevemos.
- **Modelos de Linguagem de Grande Escala (LLMs):** São modelos treinados com volumes gigantescos de dados textuais para conseguir gerar e entender textos de forma incrivelmente eficiente, com uma semântica muito próxima à nossa.

**Ferramentas Práticas:**
Ao longo das próximas aulas, a instrutora pontuou que vamos utilizar ferramentas de mercado que abstraem essa parte técnica pesada e facilitam a nossa interação direta com a IA. Entre elas, focaremos bastante no:
- **ChatGPT** (da OpenAI)
- **Microsoft Copilot**

---

## Aula 3: O que vamos explorar neste curso?

**O que aprendi nesta aula:**
Nesta aula, a instrutora apresentou um panorama (overview) completo de tudo o que vamos aprender. O conteúdo do curso foi dividido para nos ajudar a elevar a qualidade dos nossos prompts ao próximo nível, passando pelos seguintes pilares:

1. **Visão Geral e Funcionamento da IA:**
   - Como os modelos de linguagem realmente "entendem" um prompt.
   - Como funciona o processamento dessas informações através de **Tokens**.
   - Como as IAs conseguem lembrar do que foi dito anteriormente na conversa, através do conceito de **Janela de Contexto**.

2. **A Arte de Formular um Bom Prompt:**
   - Quais são os elementos essenciais para estruturar um comando perfeito.
   - Como exemplo prático, veremos a criação de uma história e ambientação para um RPG de mesa!

3. **Aplicações Práticas e Cuidados:**
   - Como utilizar a Engenharia de Prompts no dia a dia, tanto para otimizar tarefas da vida pessoal quanto da vida profissional.
   - **Cuidados na aplicação:** Um alerta muito importante sobre os riscos, limitações e boas práticas ao usar os modelos de IA.
