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
