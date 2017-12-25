## Brief description on Question Answering via Knowledge graph

Knowledge graph is widely used to answer questions. Generally, there are three components in a QA system: question interpretor, which is responsible for parsing the questions in natural language, and understanding the intents of questioners; knowledge graph based reasoning engine, which is to query and reason answers to these questions, and; answer generator, which can organize the answers and translate them into natural language.

The common types of questions in Knowledge Graph based QA contains:

+ Entity recognition
+ Disambiguation
+ Relation classification
+ Segmentation

## Available Knowledge Graphs

+ [DBpedia](http://dbpedia.org)
+ [WikiData](https://www.wikidata.org)
+ [Google's Knowledege Graph]
+ [Microsoft Bing's Satori Knowledge Base]
+ [Yandex' Object Answer]

## Challenges
(From Neural Network-based Question Answering over Knowledge Graphs on Word and Character Level)
+ Lexical Gap – surface forms for relations expressed in a question can be quite different from those used in the KG
+ Ambiguity – the same word is used for different entities, such as president of a company or a country,
+ Unknown knowledge boundaries – QA systems can often hardly decide whether a certain question is answerable at all give a certain knowledge base

## Technique Comparison

| Technique        | Question           | Algorithm  |    Novelty |
| -------------    |:------------------:| ----------:| -----------|
| [1]              | Entity prediction | Gated Recurrent Unit + RNN | Character- and word-level representations for questions |
| [2] KnowBot      | 

## Referred papers

+ Neural Network-based Question Answering over Knowledge Graphs on Word and Character Level, IW3C2 2017
+ Learning Knowledge Graphs for Question Answering through Conversational Dialog
