# Tasks

- It is perfectly fine if you have no experience in the field and trying it out for the first time. Please put in sincere efforts and try to learn from whatever you complete!
- Each Task has an ID, tags, mentor, description, tips and useful resources
- You can refer to the resources put up in each task to understand the concepts required to complete the task.
- Feel free to reach out to the mentors for any assistance you need.
- Mention the Task ID attempted in the README of your private GitHub repository.
- Read the instructions, evaluation criteria and submission details [here](./README.md)

### Table of contents

| Task                                                                | Difficulty  |
| ------------------------------------------------------------------- | ----------- |
| [Example Task](#task-id-example-task)                               | Medium      |
| [Emojify](#task-id-emojify)                                         | Easy/Medium |
| [Web-Based Diagram Generator](#task-id-web-based-diagram-generator) | Medium      |

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

## Task ID: Web-Based Diagram Generator

#### `Full-Stack Development`, `Diagram Generation`, `Graphviz`

Mentors: [Shubham Subodh Rasal](https://github.com/Shubham-Rasal) ([+91 7349784770](https://wa.me/917349784770)), [Udit Jain](https://github.com/UditJain2622004) ([+91 8708596606](https://wa.me/918708596606))

Difficulty: `Medium`

### Description

Develop a web application inspired by _Mermaid.js_ that enables users to generate various types of diagrams based on user input. Users can enter data or upload relevant files, and the system will produce the desired diagram. Focus on letting users generate diagrams with minimal input. The application should also provide the option to export the generated diagram in popular formats like PNG and PDF.

#### Popular Diagrams:

- Flowcharts
- ER Diagrams
- Class Diagrams
- Dependency Diagrams (for Node.js and React projects)

#### Steps:

1. **Input Mechanism**: Design a simple input system that is intuitive and allows for diagram creation, whether through form-based inputs or file uploads.
2. **Diagram Generation**:
   - Implement support for creating diagram using **Graphviz** or **D3.js**.
   - For Dependency Diagrams for Node.js/React projects, allow users to upload a zip file of the project. The tool should parse the project’s dependencies and visualize the relationship between files and external packages.
3. **Export Functionality**: Provide an option for users to export their diagrams in popular formats like PNG or PDF.

### Useful Resources:

- [Graphviz](https://graphviz.org)
- [D3.js](https://d3js.org/)
- [Mermaid.js Documentation](https://mermaid.js.org/)
- [Dependency Graphs in Software Projects](https://docs.npmjs.com/cli/v6/commands/npm-ls)

### Tips

1. Build support for different types of diagrams one by one.
2. Use project analysis tools like npm, yarn, or Webpack to generate dependency graphs for Node.js and React projects. These tools can help map out the project structure automatically.
3. Leverage libraries like Graphviz or D3.js for creating clean and user-friendly visualizations. These libraries are flexible and can handle a wide range of diagram types.
4. Focus on the user experience by ensuring that users can generate diagrams with the least amount of manual effort. Implement features like pre-filled options where possible.
<!-- add more here -->
