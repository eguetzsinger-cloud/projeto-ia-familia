# Especificação do fluxo

## Objetivo

Testar um fluxo controlado de IA para analisar um caso fictício de Direito de Família, utilizando fontes selecionadas manualmente.

## Entrada

A entrada principal será `apoio/caso_sanitizado.md`.

## Fontes autorizadas

Somente:
- `apoio/fonte_1.md`
- `apoio/fonte_2.md`

## Tarefa

A IA deverá:
1. identificar os pontos jurídicos relevantes;
2. relacionar cada afirmação às fontes disponíveis;
3. indicar arquivo e trecho utilizado;
4. separar fato do caso, informação jurídica e inferência;
5. apontar o que precisa de revisão humana.

## Restrições

- não utilizar fatos externos ao caso;
- não inventar artigos;
- não inventar decisões judiciais;
- não utilizar fontes não listadas;
- não apresentar conclusão definitiva;
- não ocultar incertezas.

## Público

Professor e estudante responsável pela atividade.

## Critérios de aceitação

A resposta será aceita somente se:
- respeitar as fontes autorizadas;
- apresentar referências aos arquivos;
- diferenciar fatos e análise;
- registrar limitações;
- permitir conferência humana.
