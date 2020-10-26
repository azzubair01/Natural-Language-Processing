# Natural Language Processing
This repository can be referred for Named Entity Recognition, Relation Extraction, and Coreference Resolution Tasks using StanfordCoreNLP. Note that the text used here is about Huawei which is taken from Wikipedia.

## 1) Named Entity Recognition
- <b>Definition</b>: 
  - Named-entity recognition is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc. (Wikipedia,nd.)
- <b>Entities recognised</b>:
  - PERSON
  - LOCATION
  - ORGANIZATION
  - etc.
  
 ## 2) Relation Extraction
 - <b>Definition</b>:
   - Relationship extraction is the task of extracting semantic relationships from a text. Extracted relationships usually occur between two or more entities of a certain type (e.g. Person, Organisation, Location) and fall into a number of semantic categories (e.g. married to, employed by, lives in).
- <b>Relations recognised</b>:
  - per_employee_of
  - per_member_of
  - per_origin
  - etc.
  
 ## 3) Coreference Resolution 
 - <b>Definition</b>:
   - In linguistics, coreference, sometimes written co-reference, occurs when two or more expressions in a text refer to the same person or thing; they have the same referent, e.g. Bill said he would come; the proper noun Bill and the pronoun he refer to the same person, namely to Bill. (Wikipedia, nd.)
 - <b>Examples</b>:
   - Cluster 1 = [Maybank, the bank, it] 
   - Cluster 2 = [Bill, He, his, him]

## Note that this repository requires libraries such as:
- tqdm
- pandas
- stanza
- allennlp
- stanfordnlp
- allennlp_models
