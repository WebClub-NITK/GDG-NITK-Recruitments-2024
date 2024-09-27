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
| [AgriVerify](#task-id-agriverify)                            | Medium/Hard  |




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

<!-- add more here -->




## Task ID: AgriVerify

#### `Web Application`, `Blockchain`, `Smart Contracts`

Mentors: [Mardav Gandhi](https://github.com/marcdhi) ([+91 9033398366](https://wa.me/9033398366)), [Krishna Tulsyan](https://github.com/krishna) ([+91 9506221135](https://wa.me/9506221135))

Difficulty: `Medium`

### Description

Welcome to **AgriVerify**, where we blend blockchain technology with organic farming to bring trust and transparency to every crop grown! In this task, you’ll be creating a decentralized platform that empowers farmers to easily certify their organic produce and generate QR codes that consumers can scan for instant verification.

Imagine walking through a market, scanning a QR code on an apple, and instantly seeing its certification, the farm it came from, and the people behind it—all with the power of blockchain!

This task will take you through the exciting world of Web3, where you’ll learn how to create and deploy smart contracts, integrate them into a sleek frontend, and give farmers the tools they need to show the world the purity of their crops. 🌱✨

This isn’t just about building a platform—it’s about creating a future where people can truly trust the food they eat. You’re making the world a little more transparent, one QR code at a time! 🌍🌾

---

### Steps to Complete the Challenge:

1. **Farmer Onboarding:**  
   Build a welcoming system where farmers can easily sign up using wallet authentication and request certification for their crops. The process should be seamless, ensuring the user experience is as simple as organic farming itself.

2. **Certification Process:**  
   Dive into smart contracts! Implement a contract where farmers submit their crops for certification. For simplicity, assume the certifications are auto-approved. The goal is transparency and accessibility.

3. **QR Code Generation:**  
   Generate QR codes for certified crops. These codes should link to a beautifully simple page showing the certification details stored on the blockchain, enabling consumers to instantly trust their food.

---

### Optional Feature (Hard Level Task):

**Push Notifications:**  
Add that extra touch by integrating **Push Protocol** to notify farmers in real-time when their crops are certified. Keep them excited and informed with instant updates!

---

### Useful Resources:
- [Ethereum Smart Contracts Documentation](https://ethereum.org/en/developers/docs/smart-contracts/)
- [Hardhat Documentation](https://hardhat.org/getting-started/)
- [QR Code Generation with JavaScript](https://www.npmjs.com/package/qrcode)
- [Push Protocol Integration Guide (optional)](https://docs.push.org/developers/developer-guides/protocol/overview)

---

### Tips:
- Focus on creating an easy-to-use platform where farmers feel confident certifying their crops.
- Use smart contract libraries like **OpenZeppelin** to ensure security and accelerate development.
- Keep the frontend user-friendly, ensuring a fun and smooth experience for both farmers and consumers.

---
