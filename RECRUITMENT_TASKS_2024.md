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
| [Fast-Type](#task-id-fast-type)                        | Medium          |


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
### Task ID: Fast-Type

#### `Web Development`,`Frontend`,`Backend`,`WebSockets`

Mentors: [Aahil Rafiq](https://github.com/AahilRafiq) ([+91 7975657621](https://wa.me/917975657621)), [Shree Harsha Bhat](https://github.com/mshreeharsha) ([+91 9739835034](https://wa.me/919739835034))

Difficulty: `Medium`

### Description

Build a typing speed test app like [Monkeytype](https://monkeytype.com/). The app should let users take a typing test based on either time (e.g., 60 seconds) or a fixed number of words (e.g., 50 words).

Include the following features:

1. Show the typing speed (words per minute) and accuracy after the test.
2. Provide analytics on the user's typing:
   - Speed and accuracy stats
   - A graph showing how typing speed changes over time during the test
3. Create a daily leaderboard and an all-time leaderboard to display the top typers.
4. See that frontend provides a good user experience, including real-time updating of letters typed , correct marking of letters and good looking UI.
5. **Bonus:** Show how a user's typing speed improves over time.
6. **Bonus:** Add a multiplayer mode where users can race with 5 random people online.

### Useful resources:

- [Chart.js](https://www.chartjs.org/)
- [SpeedTypingOnline (How to calculate WPM and accuracy)](https://www.speedtypingonline.com/typing-equations)
- [Socket.io](https://socket.io/)

### Tips

1. Start with a basic typing test that records speed and accuracy.
2. For leaderboards, use a simple database to store results and calculate rankings.
3. For the graph, use Chart.js to visualize typing speed over time.

## Task ID: Clubs Recruitment Portal

#### `Full stack web development`, `Frontend`, `Backend`

Mentors: [Sanjeev Holla S](https://github.com/sanjeevholla26) ([+91 7676977619](https://wa.me/7676977619)), [Fahim Ahmed](https://github.com/ahmedfahim21) ([+91 8861054452](https://wa.me/8861054452))

Difficulty: `Hard`

### Description

Develop a web application that streamlines the entire clubs recruitment process, from announcing recruitment schedules to revealing the final selected candidates, ensuring a hassle-free experience for both clubs and participating students.

## Features to Implement:

1. **Club Convenors Registration**: Club convenors should be able to register their clubs on the platform.

2. **Student Announcements**: Students should be able to view a list of clubs along with announcements regarding recruitment schedules.

3. **Club Preference Form**: An admin-released club preference form should be available during exclusive club recruitment, allowing students to fill out their preferences.

4. **Recruitment Details**: Clubs should be able to input details about their recruitment process, including the schedule and test links (if applicable).

5. **Student Registration**: Students should be able to register for the recruitment process of multiple clubs.

6. **Recruitment Rounds**: Clubs should be able to manage and track students across multiple rounds in the recruitment process.

7. **Final Announcements**: Clubs should be able to announce their final selected candidates at the end of the recruitment process.

## Bonus Feature (Optional):

1. **Integrated Calendar**: To manage the hectic nature of club recruitment, integrate a calendar feature where students can view the recruitment schedules of all clubs.

### Useful resources:

- [Django](https://docs.djangoproject.com/en/4.0/intro/tutorial01/)
- [ReactJS](https://react.dev/)
- [NodeJS](https://nodejs.org/en)
- [Bootstrap](https://getbootstrap.com/docs/5.2/getting-started/introduction/)

### Tips

1. Start by deciding a subset of features:
   Begin by selecting a subset of the features mentioned above that you want to implement first. This will help you build an MVP (Minimum Viable Product) and then gradually add more features.

2. Design an efficient database schema:
   Create a well-thought-out database schema that efficiently organizes data for clubs, students, recruitment rounds, announcements, and schedules.

3. Choose suitable frameworks:
   You can choose to use a full-stack framework like Django or Ruby on Rails to simplify the development of both the backend and frontend. Alternatively, you can use React/Next.js for the frontend and create APIs to connect to the backend services.

4. Implement proper role-based access control (RBAC):
   Ensure that the platform remains secure by implementing proper role-based access. Define roles like Admin, Club Convenor, and Student, ensuring that each role has the necessary permissions to perform actions on the platform.

