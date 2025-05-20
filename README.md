# azure-ai-102

https://exampro.co/ai-102

Code samples - https://github.com/ExamProCo/Azure-Examples

Py code executed using AI ML studio - JupyterNotebook, with min compute allocation

Sample 1 - Translator service

azure.ai.translator.text import Text TranslationClient Method --> translate

Search in google - github azure ai translator sdk samples Resources: https://github.com/Azure/azure-sdk-for-python/blob/main/sdk/translation/azure-ai-translation-text/README.md

Sample 2 - AzueOpenAI
from openai
client.chat.completions

Sample 3 - prompt flow

Sample 4 -
Azure AI search
https://github.com/Azure/azure-search-vector-samples/tree/main/demo-python/code/basic-vector-workflow

Sample 5 - Diagnostic setting
Azure AI servicess --> Diag settings
Created storage acc and log analytics workspace
Create diag settings, and then from py code, run the code that hits AI services(API key and endpoint)

https://learn.microsoft.com/en-us/azure/ai-services/cognitive-services-container-support


----------
Links
----------
https://aidemos.com/
Deploy AI service on Az containers - https://learn.microsoft.com/en-us/azure/ai-services/translator/containers/install-run?tabs=connected
Azure AI services container images can be found in the Microsoft Artifact Registry catalog.
Example - https://mcr.microsoft.com/en-us/artifact/mar/azure-cognitive-services/translator/text-translation/tags

----------
Terminology
----------
Azure Ai studio has more models under model catalog than azure openai studio

Tokenization alogo differs on LLM models like SentencePiece
Embeddings - vectors of data used by model to find relationships
Positional encoding - order of words
Attention - word importance/word weight

ML - Supervised vs Unsupervised vs Reinforcement
GPU - parallel computing tasks

Best IDE - JupyterLab

---------------
Responsible AI
---------------
1. fairness - FairLearn python project
2. Transparent - 
3. Reliable and safely
4. Privacy and security
5. Inclusiveness
6. Accountability

)
