# All CPU, GPU-less RAG Model with Qdrant, Langchain, and GPT4All x Mistral-7B

This documentation outlines the integration of a Retriever-Augmented Generation (RAG) model that leverages the power of Qdrant for similarity search, Langchain for text splitting, and the GPT4All x Mistral-7B model for generating responses. This setup is designed to work entirely on CPU, offering a cost-effective solution for deploying advanced AI models.

## Resources

- **GPT4All Website**: Visit [GPT4All](https://gpt4all.io/index.html) for more information on the platform.
- **Model Details**:
  - **Creator**: TheBloke
  - **Model Name**: mistral-7b-instruct-v0.1.Q4_0.gguf
  - **Hugging Face Link**: [Mistral-7B-Instruct-v0.1-GGUF by TheBloke](https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF)
- **Original Model**:
  - **Creator**: MistralAi
  - **Hugging Face Link**: [Mistral-7B-Instruct-v0.1 by MistralAi](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1)
- **Research Paper**: The paper about the model can be accessed [here](https://arxiv.org/pdf/2310.06825.pdf).

## Libraries Utilized

- **[Langchain](https://python.langchain.com/docs/get_started/introduction/)**: Used for text splitting.
- **[Qdrant](https://qdrant.tech/documentation/)**: Utilized for similarity search and vector storage.
- **[GPT4All](https://docs.gpt4all.io/index.html)**: The backbone model platform.

## Use Case: Recipe Recommendation System

This setup is demonstrated through a use case of a recipe recommendation system, showing the model's capability in handling and generating culinary recipes upon request.

### Example Query

> **Entering new LLMChain chain...**
>
> **Prompt**: You are a chef expert bot. Below presents a context from which a question will be asked, give your valuable insights as well. Start by giving the name of the recipe, then the ingredients, then the recipe steps, always. And always end the recipe, don't stop before writing all steps.
>
> **Context**: Oreo Birthday Cheesecake recipe details...
>
> **Question**: Give me a recipe for a chocolate cake.
>
> **Answer**:
>
> Chocolate Cake Recipe
> Ingredients:
> - 2 cups all-purpose flour
> - 3/4 cup unsweetened cocoa powder
> ...
>
> Instructions:
> 1. Preheat oven to 350 degrees Fahrenheit...
>
> **Finished chain.**

This documentation provides a comprehensive overview of the GPU-less RAG model integration using Qdrant, Langchain, and GPT4All x Mistral-7B, showcasing its application in a practical use case.
