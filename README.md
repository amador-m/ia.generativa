# IA Generativa e OpenAI no Azure

## Objetivo Geral
Este repositório tem como finalidade explorar a **IA Generativa**, seus conceitos básicos e a aplicação do **Azure OpenAI** na criação de soluções baseadas em modelos de linguagem.

## Conteúdo Abordado
- Conceitos básicos de IA Generativa
- Modelos de linguagem grandes (LLMs)
- Funcionamento da arquitetura Transformer
- Aplicação do **Azure OpenAI** e seus modelos
- Engenharia de prompts para IA Generativa
- IA Generativa responsável

## O que é IA Generativa?
A **IA Generativa** é um tipo de inteligência artificial que cria conteúdo original sem precisar de instruções explícitas sobre o que gerar. Essa tecnologia pode produzir:
- **Geração de linguagem natural** – Criação de textos coerentes e interativos.
- **Geração de código** – Tradução de linguagem natural em trechos de código.
- **Geração de imagens** – Criação e edição de imagens usando modelos como **DALL-E**.

### Modelos de Linguagem Grandes (LLMs)
Os modelos de IA generativa são alimentados por **LLMs (Large Language Models)**, um tipo especializado de aprendizado de máquina focado no **processamento de linguagem natural** (PLN). Esses modelos realizam tarefas como:
- Análise de sentimento
- Resumo de textos
- Comparação semântica entre diferentes fontes
- Geração de linguagem natural de maneira autônoma

## Arquitetura Transformer
Os **LLMs** são baseados na arquitetura **Transformer**, composta por dois blocos principais:
1. **Codificador** – Cria representações semânticas do vocabulário de treinamento.
2. **Decodificador** – Gera sequências de linguagem a partir dessas representações.

Para isso, o processo envolve:
- **Tokenização**: Decomposição do texto em **tokens** numéricos únicos.
- **Inserções**: Relações entre tokens representadas como vetores multidimensionais.
- **Atenção**: Técnica que captura a importância dos tokens dentro de uma sequência.

## O OpenAI do Azure
O **Azure OpenAI** permite implementar modelos de IA generativa na nuvem da Microsoft com segurança e personalização. Ele oferece suporte a:
- Modelos **GPT-4** e **GPT-3.5**, capazes de gerar texto e código.
- Modelos de **Embeddings**, úteis para análise semântica de dados.
- **DALL-E**, um modelo de geração de imagens baseado em descrições textuais.

### Como utilizar o OpenAI do Azure?
O Azure OpenAI pode ser acessado por meio de:
- **Azure AI Studio** – Interface para criação e implantação de modelos.
- **Playgrounds** – Ambientes de teste sem necessidade de código.
- **APIs REST** e **SDKs** – Ferramentas para desenvolvedores integrarem IA em aplicativos.

## Copilotos de IA
Os **copilotos** são assistentes de IA generativa integrados a aplicativos para aumentar a produtividade e criatividade. Exemplos incluem:
- **GitHub Copilot** – Geração automática de código para desenvolvedores.
- **Microsoft Bing Chat** – Chat baseado em IA para buscas e suporte.
- **Copilot no Microsoft Edge** – Assistente de produtividade integrado ao navegador.

## Engenharia de Prompts
A qualidade das respostas de IA generativa pode ser aprimorada por meio da **engenharia de prompts**, usando:
- **Linguagem direta** – Especificação clara do tipo de resposta desejada.
- **Mensagens do sistema** – Definição do estilo de resposta do modelo.
- **Exemplos** – Aprendizado baseado em demonstrações anteriores.
- **Dados básicos** – Informações de contexto para refinar respostas.

## IA Generativa Responsável
O desenvolvimento de IA generativa deve considerar aspectos de **ética e responsabilidade**. Para isso, o planejamento segue quatro fases:
1. **Identificar** possíveis danos potenciais.
2. **Medir** a presença de problemas nas respostas.
3. **Mitigar** impactos negativos com ajustes adequados.
4. **Operar** com responsabilidade, garantindo uma implantação segura.
