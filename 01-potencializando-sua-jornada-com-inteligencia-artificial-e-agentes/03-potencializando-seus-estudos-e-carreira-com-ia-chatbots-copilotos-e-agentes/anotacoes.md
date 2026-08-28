# Anotações: Potencializando Seus Estudos e Carreira com IA (Chatbots, Copilotos e Agentes)

Este documento reúne minhas anotações ao longo das aulas deste curso.

---

### Módulo: Sua Jornada Começa Aqui

## Aula 1: De Chatbots a Agentes, o Caminho que Vamos Percorrer

**O que aprendi nesta aula:** 
O foco aqui foi entender como podemos usar a Inteligência Artificial, na prática, para dar um gás nos nossos estudos e na nossa carreira em tecnologia. O professor ressaltou algo muito legal: não precisamos ter experiência prévia com IA, pois o conteúdo vai partir do zero!

Anotei que a nossa interação com a IA vai evoluir em três níveis, do mais básico ao mais autônomo:

1. **Chatbots (O Consultor):** É o nível inicial. É como se eu estivesse consultando um especialista. Eu faço uma pergunta, ele me dá uma resposta. Bem direto ao ponto.
2. **Copilotos (O Colega de Trabalho):** Aqui a coisa já fica mais dinâmica. É como ter um colega do lado olhando o que eu estou fazendo (seja um código ou um documento) e me dando sugestões de melhorias ou completando minhas frases em tempo real.
3. **Agentes (O Assistente de Confiança):** Esse é o nível máximo de autonomia. É como se eu delegasse uma tarefa para alguém de confiança. Eu só digo o que eu preciso (o objetivo final) e o agente se vira para raciocinar, usar ferramentas e me entregar a solução pronta.

> [!IMPORTANT]
> **Conceitos > Ferramentas**
> Uma dica de ouro que o professor deu: o cenário de IA muda tão rápido que novas ferramentas surgem e somem o tempo todo. Por isso, eu não devo me apegar cegamente a uma ferramenta específica, mas sim **entender os conceitos por trás delas**. Entender a lógica do que é um chatbot, um copiloto e um agente é o que vai me permitir escolher e usar qualquer tecnologia no futuro! O professor também avisou que o repositório do curso será atualizado periodicamente para acompanhar essas mudanças no cenário da IA.

---

### Módulo: Pergunte e Receba Respostas Inteligentes (Chatbots)

## Aula 1: Como uma boa pergunta muda tudo

**O que aprendi nesta aula:**
Nesta aula, nos aprofundamos no primeiro nível de interação que vimos anteriormente: os **Chatbots**. O professor fez uma analogia muito boa: podemos pensar no chatbot como um consultor particular que está disponível 24 horas por dia para nós.

O fluxo de funcionamento é super simples e natural: eu descrevo a minha dúvida usando linguagem natural e a IA processa isso para me responder da maneira mais adequada possível, baseada no conhecimento que ela tem.

Mas o grande "pulo do gato" da aula foi entender o conceito de **Prompt**. 

**O que é um Prompt?**
Em resumo, o prompt é o conjunto de informações (ou comando) que passamos para as LLMs para que elas processem a nossa pergunta. E aqui entra a regra de ouro: *não existe mágica!* A qualidade da resposta que a inteligência artificial vai me dar está diretamente ligada à qualidade do meu prompt.

O professor comparou isso com tirar uma dúvida com um professor na escola:
- Se eu faço uma pergunta vaga, recebo uma resposta genérica.
- Se eu trago **maior clareza, riqueza de detalhes e aprofundamento/fundamentação** na minha pergunta, o professor (ou, no caso, o chatbot) consegue me dar uma resposta muito melhor e alinhada com o que eu realmente preciso. 

Ou seja, para extrair o máximo do "consultor", o segredo está no detalhamento. Quanto mais rica a pergunta, mais rica a resposta!

---

## Aula 2: Descobrindo o Seu Caminho na Tecnologia

**O que aprendi nesta aula:**
Nesta aula, fomos colocar a mão na massa! O objetivo era conversar com alguns chatbots para descobrir uma área de tecnologia que combinasse com o meu perfil. 

Para que o teste fosse justo e sem o viés de pesquisas que eu já tinha feito antes, fiz tudo em abas anônimas e sem estar logado (testei no ChatGPT e no Google Gemini, já que o Copilot e o Claude exigem login). O mais legal é que, mesmo como visitante anônimo, os modelos entregam respostas muito boas. O professor também comentou sobre recursos bem interessantes que os chatbots modernos têm, como anexar arquivos, enviar áudios e a velocidade de resposta dos modelos.

O professor disponibilizou um template base de prompt para usarmos:

```text
Quero entrar na área de tecnologia, estou em transição de carreira e tenho 1h por dia para estudar.
Meu background é em [sua área de origem, ex.: Psicologia].

Me ajude a decidir por onde começar. Responda assim:

1. Três áreas que combinam com meu perfil, em ordem de afinidade
2. Uma sugestão final de qual escolher e o porquê
3. Cinco tópicos iniciais para estudar nessa área

Use linguagem simples, como se fosse uma conversa com um amigo.
```

Como eu já sou da área de T.I., para conseguir fazer o exercício prático e testar a capacidade de raciocínio do modelo na transição de carreira, tive que "inventar" um background. Resolvi simular um perfil misturando Psicologia e Arquitetura/Urbanismo. Adaptei o template para o meu cenário fictício da seguinte forma:

```text
Quero entrar na área de tecnologia, estou em transição de carreira e tenho 1h por dia para estudar.
Meu background é em Psicologia e Arquitetura e Urbanismo, onde atualmente trabalho com desenho de peças em ferramentas CAD com um controle de qualidade industrial. Adicionalmente, gosto de aplicar técnicas de psicologia em meu dia a dia para entender melhor as pessoas e entregar as minhas demandas com mais qualidade.

Me ajude a decidir por onde começar. Responda assim:

1. Três áreas que combinam com meu perfil, em ordem de afinidade
2. Uma sugestão final de qual escolher e o porquê
3. Cinco tópicos iniciais para estudar nessa área

Use linguagem simples, como se fosse uma conversa com um amigo.
```

**Minha Análise dos Resultados:**
Ambas as IAs compartilharam uma base estrutural muito similar, respondendo diretamente ao meu cenário. As duas elegeram **UX Design** como a melhor opção (número 1), justificando que a área aproveita de imediato a empatia e pesquisa da Psicologia com o senso espacial e estético da Arquitetura. Ambas também sugeriram Gestão de Produto (Product Design) como segunda opção e traçaram uma trilha inicial de estudos praticamente idêntica (fundamentos de UX, pesquisa com usuários, arquitetura da informação e Figma).

As principais diferenças ficaram no tom da conversa, na terceira carreira sugerida e no desfecho:
- **ChatGPT:** Adotou uma postura mais analítica e profissional. Ele indicou QA (Quality Assurance) como terceira via (por causa da minha experiência atual com controle de qualidade industrial) e propôs uma validação bem concreta, sugerindo um experimento de 30 dias para eu criar um mini-projeto prático de portfólio.
- **Google Gemini:** Usou uma linguagem muito mais informal e entusiasmada. Ele sugeriu Front-end Development como terceira alternativa (embora tenha descartado logo em seguida por causa do meu tempo escasso de estudo) e encerrou de forma mais interativa, me convidando a continuar a conversa para detalhar a rotina de estudos.

📁 **Confira as respostas completas:**
- [Resultado ChatGPT](./exemplos/modulo-02-aula-02/Output-Transição-ChatGPT.pdf)
- [Resultado Google Gemini](./exemplos/modulo-02-aula-02/Output-Transição-Google-Gemini.pdf)

---

## Aula 3: Questionário Prático (Módulo 2)

**O que aprendi nesta aula:**
Para fechar esse módulo com chave de ouro, tivemos um questionário prático avaliando os conceitos que exploramos nas últimas aulas. O teste foi totalmente focado no uso inteligente dos prompts e relembrou exatamente o caso de uso prático que fizemos: a transição de carreira misturando Psicologia e Arquitetura/CAD.

Como o desafio envolvia responder questões de múltipla escolha baseadas nessa análise com as IAs e na analogia do professor, documentei separadamente todas as perguntas, as respostas que eu acertei e tirei prints de cada etapa para registrar meu progresso (incluindo o resultado final gabaritado!).

🏆 *Você pode conferir o documento com o registro completo deste questionário, junto com as imagens, na nova pasta de desafios:* [Desafio do Módulo 2](./desafios/modulo-02-questionario-pratico/questionario-modulo-02.md)
