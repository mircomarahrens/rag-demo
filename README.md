# Retrieval-augmented generation with quantized open-source large language models

... or me learning LLMs.

- original model: <https://huggingface.co/mistralai/Mistral-7B-v0.1>
- quantized model: <https://huggingface.co/TheBloke/Mistral-7B-v0.1-AWQ>
- vllm: <https://docs.vllm.ai/>
- autoawq:
    - <https://docs.vllm.ai/en/latest/quantization/auto_awq.html>
    - <https://github.com/casper-hansen/AutoAWQ>

<!-- ## Architectural overview

```mermaid
sequenceDiagram
    User->>WebUi: Prompt
    WebUi->>Alice: Great!
    Alice-)John: See you later!
``` -->

## References

- <https://huggingface.co/TheBloke/SciPhi-Self-RAG-Mistral-7B-32k-AWQ>
- <https://github.com/oobabooga/text-generation-webui>
- <https://medium.com/@thakermadhav/build-your-own-rag-with-mistral-7b-and-langchain-97d0c92fa146>
- <https://redis.io/docs/get-started/vector-database/>
- <https://github.com/facebookresearch/faiss/wiki>
- <https://github.com/TimDettmers/bitsandbytes>
- <https://www.youtube.com/watch?v=IxrlHAJtqKE>
- <https://research.ibm.com/blog/retrieval-augmented-generation-RAG>
- NLP Course: <https://huggingface.co/learn/nlp-course/chapter1/1>
- Quantization: <https://huggingface.co/docs/transformers/main_classes/quantization>
- Tokenizer: <https://huggingface.co/docs/transformers/main_classes/tokenizer>
- <https://python.langchain.com/docs/integrations/vectorstores/faiss>
- <https://python.langchain.com/docs/modules/data_connection/document_loaders/pdf>
- <https://openai.com/blog/introducing-text-and-code-embeddings>

## Paper

- RAG: <https://arxiv.org/abs/2005.11401v4>
- MistralAI paper: <https://arxiv.org/pdf/2310.06825.pdf>
- OpenAI Text embeddings paper: <https://arxiv.org/abs/2201.10005>

## TODOs

- add bash script for model download
- add vector database
- add custom data (pdfs)
- add api server serving model

## Others

- <https://rise.readthedocs.io/en/latest/>
