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

---

### Módulo 2: Visão Geral da Engenharia de Prompts

## Aula 1: Como os Modelos de Linguagem "Entendem" um Prompt?

**O que aprendi nesta aula:**
Para iniciar nossa visão geral sobre a engenharia de prompts, a instrutora explicou a forma técnica de como as IAs interagem com o texto. 

As LLMs (Modelos de Linguagem de Grande Escala) não "entendem" as palavras da mesma forma que os humanos. Ao invés disso, elas se apoiam em **cálculo probabilístico** com base em padrões absurdamente complexos aprendidos durante sua fase de treinamento.

**A Arquitetura Transformer e o Mecanismo de Atenção:**
Esses modelos de inteligência artificial são fundamentados principalmente na arquitetura **Transformer**, um marco revolucionário na tecnologia que foi detalhado no artigo científico clássico *Attention Is All You Need*. 
*(Deixei salvo aqui o link de apoio para uma tradução do artigo: [Tradução - Attention Is All You Need](https://medium.com/@msmurilo/tradu%C3%A7%C3%A3o-artigo-attention-is-all-you-need-2f7a4113b3be)).*

O grande trunfo do Transformer é o seu **Mecanismo de Atenção**. Ao invés de ler e processar as palavras engessadamente de maneira linear (uma após a outra isoladamente), ele analisa as palavras em sequência considerando o contexto e o "peso" de cada palavra em relação a todas as outras do texto.

> **Analogia do Editor Experiente:**
> Imagine que a IA é um editor revisando a frase: *"Ana pegou um livro porque achou interessante"*. Para compreender, o editor não lê apenas palavra por palavra e vai em frente; ele retrocede mentalmente e busca conexões: "Quem é Ana?", "Por que o livro é interessante?". De maneira simplista, o mecanismo de atenção faz exatamente isso: cria conexões cruzadas em diferentes partes do texto sem seguir uma ordem rígida, destacando os trechos relevantes. Isso resulta em respostas rápidas, mais coerentes e contextualmente perfeitas.

**O Passo a Passo: Do Prompt até a Resposta:**
Como os modelos processam os nossos comandos, de fato? Quando enviamos um prompt, ocorre o seguinte fluxo:
1. **Tokenização:** O texto é quebrado em "Tokens" (unidades básicas que podem ser palavras inteiras, partes de palavras ou até simples caracteres). É importante notar que a tokenização varia de acordo com cada modelo de IA e também pelo idioma do texto.
   
   *Exemplo da aula no Tokenizer da OpenAI:*
   ```text
   A DIO é a primeira plataforma Open Education brasileira dedicada a tornar o conhecimento em tecnologias exponenciais acessível a todos.
   ```
   A frase acima é traduzida pelo algoritmo em uma lista de exatos **24 tokens** (considerando modelos GPT-5.x & O1/3).

   <br>
   <div align="center">
     <em>Análise de Tokens: OpenAI Tokenizer</em><br>
     <img src="./exemplos/modulo-02-aula-01/resultado-tokenizer.png" alt="Resultado do Tokenizer da OpenAI" width="600">
     <br>
     <sup>Fonte: Autoral (2026)</sup>
   </div>
   <br>

2. **Embeddings:** Os tokens gerados são convertidos em "embeddings", que são representações vetoriais matemáticas capazes de capturar o significado profundo daquela palavra.
3. **Processamento nas Camadas:** Esses embeddings passam pelas camadas das redes neurais com transformadores, operando para compreender o sentido e o contexto final da sua frase.
4. **Previsão (Cálculo Probabilístico):** Por fim, a IA não "escreve" pensando; ela gera uma distribuição de probabilidades para tentar adivinhar matematicamente qual será o próximo token da resposta. Esse loop de previsão se repete constantemente até completar a resposta enviada a nós!

Tendo entendido de maneira simplificada como os modelos entendem um prompt, na próxima aula vamos explorar como funciona a memória dessas Inteligências Artificiais.
