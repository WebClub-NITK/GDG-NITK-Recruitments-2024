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
| [Competitive Programming Portal](#task-id-competitive-programming-portal) | Medium     |


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

## Task ID: Competitive Programming Portal
#### `Mobile Application, APIs`

Mentors: [Abhishek Satpathy](https://github.com/AbhishekSatpathy4848) ([+91 7619503901](https://wa.me/917619503901)), [Aman Sheoran](https://github.com/amansheoran15) ([+91 8930460660](https://wa.me/918930460660))

Difficulty: `Medium`

### Description

Develop a mobile application that displays a unified dashboard for Competitive Programming Platforms, aggregating user information, ratings, questions solved, contest data etc from at least three platforms (e.g., Codeforces, LeetCode, AtCoder). The app should offer users a comprehensive overview of their competitive programming profile across these platforms.


Follow the steps below to complete this challenge:

1. Integrate user information like username, rating and other relevant information from at least three platforms of your choice.
2. If contests are available, show contest information for:
   - Past Contests: Show recently concluded contests with relevant details.
   - Ongoing Contests: Display currently active contests.
   - Upcoming Contests: List future scheduled contests with dates and times.
3. User's can tap on contests to view more information if available.
4. Design and implement a clean, intuitive user interface for easy navigation between different pages. Great UI/UX will add bonus points.
5. Allow the user to filter contest information by platform.
6. Use appropriate APIs to fetch up-to-date contest information.
7. Implement error handling for API failures or data unavailability.
8. Implement a backend service to handle API requests and data processing.
9. Allow the user to add upcoming contests to his calendar.
10. Feel free to add any extra information from these platforms (heatmap, recent problem submissions, number of solved questions, difficulty of questions solved etc). Adding extra information would add bonus points.
    
### Useful resources:

- [Codeforces API](https://codeforces.com/apiHelp)
- [AtCoder API](https://atcoder-api-python.readthedocs.io/en/latest)
- [Unoffical Leetcode API](https://github.com/alfaarghya/alfa-leetcode-api)
- [ReactJS](https://react.dev/)
- [NodeJS](https://nodejs.org/en)
- [Flutter](https://flutter.dev/)
- [React Native](https://reactnative.dev/)

### Tips

1. Any Mobile App Developement Technology can be used, either Native or Cross-Platform.
2. Start by exploring the different platform APIs and the information they deliver.
3. Then look into ways you can process and surface available information throught clean UI/UX.
3. In case you find platforms that don't provide API endpoints for contests, display other information available.
4. You can also use Unofficial Platform APIs, if official alternatives don't exist.
