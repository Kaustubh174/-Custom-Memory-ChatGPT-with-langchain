# Custom Memory ChatGPT with langchain

This project demonstrates the implementation of a memory-enabled chatbot using LangChain. The chatbot remembers previous inputs and responds accordingly, creating a more interactive and context-aware conversation experience.

## Introduction

In the realm of conversational AI, maintaining context across multiple turns is crucial for creating a natural and engaging interaction. This project leverages the LangChain library to implement a chatbot that retains the context of the conversation, allowing it to provide more coherent and relevant responses over time.

## Functions

The key components of this project are:

- **ChatOpenAI**: Utilizes the OpenAI language model to generate responses.
- **ConversationBufferMemory**: A memory object that stores the history of the conversation.
- **ChatPromptTemplate**: Defines the structure and format of the prompts used in the conversation.
- **LLMChain**: Chains together the language model, prompt, and memory to form a coherent conversational agent.

## Uses

This memory-enabled chatbot can be used in various applications, including:

- **Customer Support**: Providing more accurate and context-aware responses to customer queries.
- **Personal Assistants**: Enhancing user interaction by remembering past interactions and preferences.
- **Educational Tools**: Offering more personalized and continuous learning experiences.
- **Entertainment**: Creating more engaging and interactive experiences in gaming and storytelling.

## How It Works

1. **Initialization**: The `ChatOpenAI` model is initialized.
2. **Memory Object**: A `ConversationBufferMemory` object is created to store the chat history.
3. **Prompt Template**: A `ChatPromptTemplate` is defined to structure the conversation.
4. **Chain Creation**: An `LLMChain` is created to combine the language model, prompt, and memory.
5. **Conversation Loop**: A loop is established to continuously take user input, generate responses using the chain, and print the responses while storing the conversation history.


