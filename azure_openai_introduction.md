# Introdução ao Serviço Azure OpenAI

Get to know the connection between artificial intelligence (AI), Responsible AI, and text, code, and image generation. Understand how you can use Azure OpenAI to build solutions against AI models within Azure.

Conhecendo a conexão entre inteligência artificial (IA), IA responsável, geração de texto, código e imagem. Entendendo também como o Azure OpenAI pode ser utilizado para desenvolver soluções utilizados modelos de IA dentro do Azure.

Azure OpenAI está disponível para usuários da Azure e consiste de quatro componentes:
- Modelos de IA generativa pré-treinados.
- Funcionalidades customizáveis: a habilidade de refinar os modelos de IA com seus próprios dados.
- Ferramentas nativas para detectar e mitigar casos de uso irresponsável de IA.
- Segurança e acesso baseado em papeis (RBAC) em nível empresariais e redes privadas.

## Capacidades dos modelos OpenAI

Há várias categorias de funcionalidades encontradas nos modelos de de inteligência artificial do Open AI. Três deles são:

| Funcionalidade | Exemplo |
|----------------|---------|
| Geração de linguagem natural | Resumir conteúdo complexo para diferentes níveis de leitores, sugerir palavras alternativas para sentenças, entre outros |
| Geração de código de programação | Traduzir código entre diferentes linguagens de programação, identificar e solucionar bugs em código e mais |
| Geração de imagens | Gerar imagens a partir de textos |

# O que é IA generativa?

OpenAI disponibilizou seus modelos de IA para os desenvolvedores construirem aplicações poderosas, como o ChatGPT. Há muitas variações de aplicações no site do [OpenAI](https://platform.openai.com/examples).

Os modelos do OpenAI se encaixam no panorama de IA na seguinte forma:
- Inteligência artificial imita o comportamento humano para executar tarefas sem direções explícitas de qual a saída desejada.
- Algoritmos de aprendizagem de máquina recebem dados e ajustam seus modelos a esses dados para realizar predições sob os padrões encontrados pelos modelos.
- Modelos de aprendizagem profunda usam camadas de algoritmos na forma de redes neurais artificiais para retornar padrões mais complexos encontrados nos dados fornecidos.
- Modelos de IA generativa produzem novos conteúdos a partir do que foi descrito na sua entrada.

# Descrevendo o Azure OpenAI

A união entre Microsoft e OpenAI foi projetada para alcançar as seguintes metas:
- Utilizar a infraestrutura Azure, incluindo security, compliance e disponibilidade regional para ajudar usuários com aplicações de nível empresarial.
- Implantar as capacidades dos modelos OpenAI em diversos produtos Microsoft.
- Potencializar as cargas de trabalho do OpenAI utilizando o Azure.

## Entendendo as cargas de trabalho do Azure OpenAI

O Azure OpenAI suporta diversas tarefas convencionais de IA e se adapta para algumas das novas.<br>

As tarefas mais comuns são: aprendizagem de máquina, visão computacional, processamento de linguagem natural, IA conversativa, detecção de anomalias e mineração de conhecimento.<br>

Outras cargas de trabalho suportadas pelo Azure OpenAI são categorizadas pelas funcionalidades da ferramenta:
- Geração de linguagem natural
  - Complementação de texto
  - Embarcados: procurar, classificar e comparar textos
- Geração de código: gerar, editar e explicar código de programação
- Geração de imagens: gerar e editar imagens

## Relação entre Azure OpenAI e Azure AI Services

Os serviços de IA do Azure são ferramentas para resolver cargas de trabalho relacionadas à inteligência artificial e podem ser categorizadas em três grupos: Azure Machine Learning Platform, Cognitive Service e Applied AI Services.

Azure Cognitive Services tem cinco pilares: visão, diálogo, linguagem, decisão e OpenAI. Em particular, há várias capacidades sobrepostas entre os serviços cognitivos de linguagem e o OpenAI, como tradução, análise de sentimento e extração de palavras-chave.

Enquanto não há direcionamento estrito sobre quando utilizar um serviço em particular, serviço cognitivo de linguagem pode ser utilizado como há um requisito mínimo de refinamento. O Azure OpenAI pode ser mais benéfico em casos que requerem modelos generativas altamente customizados ou para pesquisa exploratória.

# Como usar o Azure OpenAI

Atualmente (07/2023), você precisa se candidatar para acessar o Azure OpenAI. Uma vez que você tem acesso, você pode usar o serviço criando um recurso OpenAI. Quando o recurso estiver criado, vocÊ pode utilizá-lo através de API's Rest, SDK em Python ou pelo Azure OpenAI Studio.

## Azure OpenAI Studio

No Azure OpenAI Studio, você pode construir modelos e implantá-los para consumo público em aplicações diversas. As capacidades do Azure OpenAI são possíveis graças à modelos de IA generativa específicos. Modelos diferentes são otimizados para diferentes tarefas, algums modelos são excelentes em resumos e respostas gerais não-estruturadas, enquanto outros são feitos para gerar código ou imagens a partir de entradas de texto.

Esses modelos incluem:
- GPT-4 que representa os modelos generativos de linguagem e código mais evoluídos.
- GPT-3.5 que pode gera linguagem natural e código baseado em prompts.
- Modelos embarcados, que convertem texto em vetores numéricos para análise.
- DALL-E que gera imagens baseadas em descrições em linguagem natural.

Os modelos Azure OpenAI podem ser treinados e customizados com refinamento.