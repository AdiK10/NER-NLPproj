# NER-NLPproj

NER(Named Entity Recognition) is an NLP task that identifies entities like people, organizations, or locations in text. In this project, I have made use of of the transformer model XLM-Roberta can be fine-tuned to perform named entity recognition (NER) across several languages.

The dataset I will be using consists of Wikipedia articles including the four most commonlly spoken languages in Switzerland German (62.9%), French (22.9%), Italian(8.4%), and English (5.9%). 
Each article is annotated with LOC (location), PER (person), and ORG (organization) tagsin the “inside-outside-beginning” (IOB2) format. In this format, a B- prefix indicates the beginning of an entity, and consecutive tokens belonging to the same entity are given an I- prefix. An O tag indicates that the token does notbelong to any entity.
