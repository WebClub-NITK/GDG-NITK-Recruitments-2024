# Tasks

- It is perfectly fine if you have no experience in the field and trying it out for the first time. Please put in sincere efforts and try to learn from whatever you complete!
- Each Task has an ID, tags, mentor, description, tips and useful resources
- You can refer to the resources put up in each task to understand the concepts required to complete the task.
- Feel free to reach out to the mentors for any assistance you need.
- Mention the Task ID attempted in the README of your private GitHub repository.
- Read the instructions, evaluation criteria and submission details [here](./README.md)

### Table of contents

| Task                                                        | Difficulty |
| ----------------------------------------------------------- |------------|
| [Example Task](#task-id-example-task)                    | Medium     |
| [Emojify](#task-id-emojify)                            | Easy/Medium     |
| [Hogwarts Q&A](#task-id-hogwarts)                  | Medium/Hard     | 


## Task ID: Example Task

#### `Natural Language Processing`, `Machine Learning`

Mentors: [John Doe](https://github.com/johndoe) ([+91 1234567890](https://wa.me/911234567890)), [Jane Smith](https://github.com/janesmith) ([+91 9876543210](https://wa.me/919876543210))

Difficulty: `Medium`

### Description

Build an AI-powered virtual assistant that can understand and respond to user queries in natural language. The assistant should be able to perform tasks such as answering questions, setting reminders, and providing recommendations.

Follow the steps below to complete this challenge:

1. Implement natural language processing to understand user input
2. Develop a knowledge base for the assistant to draw information from
3. Create a user-friendly interface for interacting with the assistant

### Useful resources:

- [Natural Language Processing with Python](https://www.nltk.org/book/)
- [Building AI Assistants with TensorFlow](https://www.tensorflow.org/tutorials)
- [Rasa: Open Source Conversational AI](https://rasa.com/)

### Tips

1. Start by focusing on a specific domain or set of tasks for your assistant
2. Use pre-trained models and APIs to accelerate development
3. Pay attention to the user experience and make interactions feel natural


## Task ID: Emojify

#### `Web Application`, `Natural Language Processing`

Mentors: [Apoorva Agrawal](https://github.com/imApoorva36) ([+91 8197404580](https://wa.me/8197404580)), [Mardav Gandhi](https://github.com/marcdhi) ([+91 9033398366](https://wa.me/9033398366))

Difficulty: `Easy/Medium`

### Description

Develop a fun and interactive app where users input text, and it automatically translates the message into emoji-based sentences. The app will primarily use a predefined dictionary to map words or phrases to corresponding emojis. Users will also have the ability to tweak the emoji translations manually by selecting from a list of alternative emojis.

_Because sometimes, the right emoji speaks louder than words!_

Follow the steps below to complete this challenge:

1. Develop a simple user interface (UI) that allows users to input text (e.g., a sentence or phrase)
2. Create a predefined dictionary that maps common words or phrases to emojis
3. Once the user enters a sentence, break it down into individual words and replace the words that have corresponding emojis with the emojis
4. After the initial translation, allow users to manually tweak the suggested emojis by selecting from a list of alternative options
5. Also add a Voice-to-Emoji Translation with integrated voice recognition so that users can speak their sentences, and the app translates them into emojis in real-time. This will add a fun element to the app

Bonus Feature ( Optional ):

_Implementing the bonus feature will make the task count as `Medium`, otherwise it will be `Easy`_
1. Emoji Sentiment Analysis having an implementation of sentiment analysis using simple NLP models (like VADER or TextBlob) to adjust emoji suggestions based on the emotional tone of the text. This can help ensure the emoji translation better reflects the mood of the original message

### Expected Input and Output Examples:

`Input: "I love pizza"`

Output: "❤️ 🍕"

`Input: "The dog is happy"`

Output: "🐶 😃"

### Useful resources:

- [Emojipedia](https://emojipedia.org/)
- [Unicode Emoji List](https://unicode.org/emoji/charts/emoji-list.html)
- [Python Speech Recognition Library](https://pypi.org/project/SpeechRecognition/)
- [Sentiment Analysis Tool VADER](https://github.com/cjhutto/vaderSentiment)
- [Sentiment Analysis NLP Library](https://textblob.readthedocs.io/en/dev/)
- [ReactJS](https://react.dev/)
- [NodeJS](https://nodejs.org/en)

### Tips

1. Start by focusing on a basic set of words for translation and expand the emoji dictionary over time.
2. Make the UI fun and interactive with features like live emoji preview as the user types.
3. Consider using libraries or frameworks like React, Vue.js, or plain HTML/CSS/JavaScript for building the interface.
4. Allow flexibility in how emojis are displayed and edited, making the user experience more enjoyable.


## Intersig Task
## Task ID: Hogwarts Q&A  
#### `Natural Language Processing`, `Generative AI`, `Retrieval-Augmented Generation`

Mentors: [Aryan Kashyap N](https://github.com/05kashyap) ([+91 8123279065](https://wa.me/918050030224)), [Fahim Ahmed](https://github.com/ahmedfahim21) ([+91 8861054452](https://wa.me/918861054452))

**Difficulty**: `Medium\Hard`

---

### Description  
Create a **RAG (Retrieval-Augmented Generation)** system that answers questions using the book **"Harry Potter and the Prisoner of Azkaban"** as the primary knowledge base. This system should be able to handle queries related to characters, spells, locations, and magical events, retrieving contextually accurate information and generating lore-true responses.

Participants will leverage this text to build a structured index for retrieval, generate embeddings, and deploy a Harry Potter-themed Q&A system. For added fun, include context references and quotes in the generated answers.

You can access the full text of the book from the following link:  
**[Harry Potter and the Prisoner of Azkaban PDF](https://ia902903.us.archive.org/12/items/FantasyFictionebookcollection/Harry%20Potter/3%20-%20Harry%20Potter%20and%20the%20Prisoner%20of%20Azkaban.pdf)**.

### **Steps to Complete the Challenge**:

1. **Data Collection & Ingestion**:  
   Download the book from the provided link and parse it into a machine-readable format. Make sure to structure the data, preserving the chapters and significant sections. You may want to split the text based on chapters, events, or specific scenes.

2. **Data Chunking & Preprocessing**:  
   Break down large paragraphs into smaller chunks of 100-150 words. Ensure that each chunk contains coherent, self-contained information.

3. **Embedding Generation**:  
   - Use a pre-trained embedding model like ``all-MiniLM-L6-v2`` from Sentence Transformers to convert each text chunk into dense vector representations.
   - The embeddings should capture semantic meaning, making it easy to retrieve the most contextually relevant text.

4. **Vector Database Integration**:  
   Store the embeddings in a vector database such as `ChromaDB`, `FAISS`, or `Milvus` for efficient similarity searches and quick lookups.

5. **Query Handling & Retrieval**:  
   - Implement a query pipeline using the embedding model to process user queries.
   - Convert the query into an embedding and use the vector database to find the `top N` most relevant text chunks.

6. **Contextual Response Generation**:  
   - Use the retrieved chunks with a generative language model (like `Gemini` or `LLaMA`) to create a coherent response that incorporates quotes and references to specific parts of the book.
   - Ensure that the generated output maintains the tone and style of the Harry Potter universe.

7. **Serve via FastAPI**:  
   - Expose your RAG system through **FastAPI** endpoints. 
The /query endpoint should accept user queries like *“What is the significance of the Marauder’s Map?”* or *“How does Sirius Black escape from Hogwarts?”* and return a contextually accurate and engaging answer. 
The endpoint should:
Accept `POST` requests with a `JSON` body containing the user's question.
Process the query through your RAG pipeline.
Return a `JSON` response with the answer, relevant quotes, and metadata
   
8. **Develop an Interface**:  
   - Build a responsive web interface using a frontend framework like React. It should have a chat-like interface for asking questions and receiving answers. Also, create a "Time-Turner" feature that allows users to view the conversation history and jump back to previous points in the chat.

### **Useful Resources**:
- **[Harry Potter and the Prisoner of Azkaban PDF](https://ia902903.us.archive.org/12/items/FantasyFictionebookcollection/Harry%20Potter/3%20-%20Harry%20Potter%20and%20the%20Prisoner%20of%20Azkaban.pdf)**  
- **[LangChain Documentation](https://python.langchain.com/docs/introduction/)**
- **[LlamaIndex Documentation](https://docs.llamaindex.ai/en/stable/)**
- **[FastAPI Docs](https://fastapi.tiangolo.com/)**
- **[Sentence Transformers for Embeddings](https://huggingface.co/sentence-transformers)**
- **[ChromaDB GitHub](https://github.com/chroma-core/chroma)**

### Tips:
1. When chunking the text, experiment with different chunk sizes and overlaps to find the optimal balance between context preservation and retrieval quality.
2. Consider adding metadata tags (chapter names, etc.) to the chunks at the time of preprocessing. this can help with retrieval.


<!-- add more here -->
