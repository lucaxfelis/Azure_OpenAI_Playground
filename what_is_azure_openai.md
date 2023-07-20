# O que é o Serviço OpenAI Azure?

O serviço Azure OpenAI provê uma API REST de acesso os modelos de linguagem GPT-4, GPT-35-Turbo e modelos embarcados. Esses modelos podem ser facilmente adaptados a uma tarefa especifica, incluindo geração de conteúdo, resumos, pesquisa semântica e tradução de linguagem natural para código. Os usuários podem acessar o serviço através de API REST, de um SDK Python ou uma ferramenta de interface gráfica online no Azure OpenAI Studio.

## Comparando Azure OpenAI e OpenAI

O serviço Azure OpenAI oferece modelos de linguagem avançada como GPT-4, GPT-3, Codex e DALL-E com a segurança e capacidade da Azure. A ferramenta co-desenvolve as APIs com OpenAI, garantindo compatibilidade e uma transição suave de uma tecnologia para a outra. <br>

Com a Azure OpenAI, os clientes recebem os benefícios da Microsoft Azure enquanto rodam os mesmos modelos do OpenAI. Ela também oferece redes privadas, disponibilidade regional, e filtragem de conteúdo resposável.

## Conceitos-chave

### Prompts & conclusões (compleitons)

O endpoint de conclusões é o componente central deste serviço de API. Essa API provê o acesso à interface entrada-saída de texto. Os usuários precisam apenas entrar com um prompt contendo um comando e o modelo gera uma resposta conclusiva, um complemento.

### Tokens

O Azure OpenAI processa texto quebrando o mesmo em vários tokens. Tokens podem ser palavras ou apenas conjuntos de caracteres. Por exemplo, a palavra `hamburguer` é separado em uma série de tokens como `ham`, `bur` e `guer`, enquanto uma palavra simples como `uva` é um token único. Muitos tokens começam com um espaço em branco.<br>

O número total de tokens processados em uma determinada requisição dependo do comprimento total dos parâmetros de entrada, saída e requisição. A quantidade de tokens processados irá afetar a latência de reposta e a vazão dos modelos.

### Recursos

Azure OpenAI é um novo produto oferecido pela Azure. Pode-se criar recursos do Azure OpenAI da mesma forma que se cria um recurso qualquer de outro produto Azure.

### Implantação

Uma vez que o recurso OpenAI foi criado, deve-se realizar o deploy do mesmo. Essa ação pode ser feita utilizando as API de deploy ou pelo Azure OpenAI Studio. As API's devem especificar o modelo que será utilizado pelo recurso.

### Engenharia de prompt

Os modelos GPT-3, GPT-3.5 e GPT-4 do OpenAI são baseados em prompt. Com esse tipo de modelo, os usuários interagem realizando a entrada de comandos por texto, enquanto os modelos respondem com um complemento. Esse complemento é a continuação dada pelo modelo ao comando em texto de entrada.<br>

Enquanto esses modelos são bastantes poderosos, seu comportamento é bastante sensível ao que é passado no prompt. Isso faz que a [Engenharia de Prompt](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/prompt-engineering) seja uma importante habilidade a ser desenvolvida.<br>

A construção de prompts pode ser difícil. Na prática, o prompt age como a configuração de pesos de um modelo para realizar uma determinada tarefa, mas é mais uma arte (empírica), do que uma ciência, que geralmente requer experiência e intuição para elaborar um prompt de sucesso.

### Modelos

O serviço provê aos usuários diferentes modelos. Cada modelo provê uma diferente capacidade e tabelas de preço.<br>

Os modelos GPT-4 são os modelos disponíveis mais poderosos. Os modelos DALL-E geram imagens a partir de prompts de texto enviados pelos usuários.

