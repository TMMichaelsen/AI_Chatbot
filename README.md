# Chatbot de Atendimento com IA - Ouvidoria-Geral do Estado de Minas Gerais

## Sobre a OGE

A Ouvidoria-Geral do Estado é o canal de interlocução entre a sociedade e o Governo. Ela auxilia diretamente o governador na fiscalização e no aperfeiçoamento dos serviços públicos, para que o cidadão seja, a cada dia, mais bem atendido.

## Motivação

A OGE é responsável pelo acolhimento de manifestações referentes ao serviços públicos prestados pelo Governo do Estado de Minas Gerais. Entretanto, o órgão recebe diariamente um alto volume de manifestações que não são de sua competência, tais como assuntos pertinentes à entes Municipais, Federais, órgãos privados ou empresas que não se subordinam ao Poder Executivo Estadual. Em números, no ano de 2023, 6% das manifestações recebidas pela OGE foram classificadas como competências diversas.

Tais manifestações direcionadas incorretamente à OGE não somente demandam tempo de análise pelos servidores públicos, elevando o tempo médio de resposta de todas as manifestações tratadas, como também gera frustração ao cidadão, que registra sua manifestação no órgão para receber apenas posteriormente a indicação do canal correto para submissão.

Desta forma, a criação de um chatbot com capacidade de análise prévia da demanda do cidadão, indicando não somente o órgão de competência como a Ouvidoria Temática responsável pela resposta de sua manifestação torna-se crucial para maior efetividade de tratamento dos entes do Poder Público Estadual.

## Sobre o Chatbot

O chatbot gerado utiliza a tecnologia de API do Google Gemini, conectando diretamente o prompt gerado pelo cidadão à Inteligência Artificial.
Tal chatbot utiliza primeiramente uma tabela de Perguntas Frequentes em busca embedded para avaliar a demanda inserida, respondendo com texto já padronizado caso possua alto grau de confiança, isto é, proximidade do texto inserido com a pergunta frequente.

Caso o prompt não possua proximidade com os textos tabelados, o prompt é lançado para modelo generativo, contendo instruções para resposta do usuário indicando os canais corretos de atendimento.
