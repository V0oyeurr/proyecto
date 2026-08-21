# proyecto
hacer un modelo de IA de pesos abiertos usando bases de datos vectoriales como base de
conocimiento para que el modelo sea capaz de consultarla y entregar respuestas sobre
consultas de documentacion interna 

## modelo de IA
ollama el gestor de modelos de ia investigar mas sobre que modelos se pueden gestinar en este mismo.
capacidad de parametros, tamaño del contexto y que sea multimodal (con multimodal se refiere a que sea cualquier tipo de archivo)
con que tenga vision y que acepte archivos pdf o imagenes para su lectura y que pueda pensar (dentro de pensamiento viene inferencia
y de inferencia viene la capacidad de los tensores y todo eso va con las capacidades ya

## requerimientos
- caddy server 
- configuraciones de nginex inverso
- nomenglaturas de quantisacion 
- inteligencia de pesos abiertos
- modelos de ia
- base de datos vectoriales
- streaming de respuestas
- 89gb de ram y tal vez 24gb de vram
- el modelo se corre de forma local
- system prompts
- inyeccion de prompts
- protocolo http de comunicaciones de IAs
- MCP
- sandbox contenedor

## referencias
- hugging face LLM curso: https://huggingface.co/learn/llm-course/chapter1/1?utm_source=chatgpt.com
- transformers (articulo): https://arxiv.org/abs/1706.03762?utm_source=chatgpt.com
- Hugging Face Tokenizers: https://huggingface.co/docs/tokenizers/main/index?utm_source=chatgpt.com
- Hugging Face Quantization: https://huggingface.co/docs/bitsandbytes/main/en/index?utm_source=chatgpt.com
- pytorch cuda: https://docs.pytorch.org/docs/2.13/cuda.html?utm_source=chatgpt.com
- arquitectura RAG(articulo): https://arxiv.org/pdf/2601.05264
- building a RAG: https://huggingface.co/blog/ngxson/make-your-own-rag
- BD Vector theory (articulo): https://dbs-research.github.io/pdf/2024_vector.pdf
- Compression laws LLM (articulo): https://arxiv.org/pdf/2504.04342
- Build a RAG with pgvector and ollama https://mydeveloperplanet.com/2025/01/22/implement-rag-with-pgvector-langchain4j-and-ollama/