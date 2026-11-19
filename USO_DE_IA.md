# Declaração de uso de Inteligência Artificial generativa

> **Regra do trabalho:** usar IA generativa é **permitido e incentivado**, mas
> **todo e qualquer uso** precisa estar declarado e detalhado em uma seção própria
> do artigo e na apresentação (vídeo). Uso não declarado é considerado **plágio** e
> leva à **nota zero** no trabalho para todo o grupo.
>
> Este arquivo é o rascunho de trabalho da declaração: preencham **ao longo** do
> projeto (não no último dia) e copiem a tabela para o artigo. Apaguem as linhas de
> exemplo e todas as marcações TODO.

## 1. Ferramentas usadas

| Ferramenta (nome e versão/modelo) | Como acessaram | Quem usou |
|---|---|---|
| _Exemplo: OpenRouter, modelo openai/gpt-6-luna_ | _chave do grupo, via código_ | _todos_ |
| _Exemplo: ChatGPT (versão gratuita)_ | _navegador_ | _Fulana_ |
| ChatGPT (gratuito) | navegador | Sidney Kenzo |
| Claude (gratuito) | navegador | Sidney Kenzo |

## 2. Usos, um por linha
## ESSES SÃO DE EXEMPLO, REMOVER NA ENTREGA DO TRABALHO
| # | Etapa | O que a IA fez | Prompt (ou resumo + link para o registro) | O que o grupo fez com o resultado |
|---|---|---|---|---|
| 1 | _Dados de treino_ | _Gerou 412 frases para 6 intenções_ | _ver `dados/prompts_llm.md`_ | _Revisamos todas; 57 descartadas, 12 rótulos corrigidos_ |
| 2 | _Chatbot_ | _Redige as respostas das intenções e do chitchat_ | _prompts em `chatbot/llm.py` + persona do `grupo.yaml`_ | _Ajustamos a persona 3 vezes após testes (seção X do artigo)_ |
| 3 | _Código_ | _Sugeriu a função que plota a curva de validação_ | _"como plotar o resultado do GridSearchCV em função de C"_ | _Adaptamos nomes e eixos; entendemos e testamos_ |
| 4 | _Escrita_ | _Revisou a gramática da Introdução_ | _"revise a gramática sem mudar o conteúdo: ..."_ | _Aceitamos parte das sugestões_ |

| # | Etapa | O que a IA fez | Prompt (ou resumo + link para o registro) | O que o grupo fez com o resultado |
|---|---|---|---|---|
| 1 | Chatbot | Formatou as intenções no grupo.yaml, baseado no texto em formato livre que foi enviado | _"Esse é o grupo.yaml, preencha a sessão de intenção"_ | Deletamos 3 intenções e reescrita de 2 |
| 2 | Classificadores | Corrigiu a implementação do classificador de árvore de decisão | _"Corrija o código de árvore de decisão que está sendo usado para ajustar os parâmetros"_ | Reescrita do código de ajuste de parâmetros de treino |
| 3 | Classificadores | Auxiliou no código que gera a tabela | _"Escreva um método que pegue essas informações 'linha de print() de classificador' e organize em um vetor e imprima as informações em uma tabela"_ | Escreveu o código de gerar informações dos classificadores em uma tabela (que também pudemos reaproveitar pros temas) |

## 3. O que NÃO foi feito com IA

Definição das intenções;
Escrita dos dados de treino e teste (que estão documentados como de origem humana);
Reunião dos documentos;
Código de ajuste de hyperparâmetro de rede neural;

## 4. Reflexão (2 a 4 frases)

TODO: onde a IA ajudou, onde atrapalhou ou errou, e como vocês verificaram o que ela produziu.
