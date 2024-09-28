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
| [Discord QuizBot](#task-id-discord-quizbot)            | Medium     |


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


## Task ID: Discord QuizBot

#### `Discord Bot`, `APIs`,`Full Stack Development`, `GenAI`

Mentors: [Anush Revankar ](https://github.com/anushrevankar24) ([+91 9482597386](https://wa.me/9482597386)), [Ayush Kumar Singh](https://github.com/Ayush4345) ([+91 9334352548](https://wa.me/9334352548))

Discord is a popular communication platform used for communities, and Discord bots can automate tasks within these servers, enhancing server functionality. In this task, you are expected to build a Discord quiz bot that allows users to select from a set of 10-20 available quizzes, answer timed questions, and view their results on a leaderboard ranked by both points and time taken. In cases where multiple users have the same points, the ranking should be determined based on the time taken per question. After completing a quiz, users should be able to view the top 10 players and their overall rank.

The task also includes building a CRUD (Create, Read, Update, Delete) application for managing quiz sets and individual questions.

**Key Features to Implement**:
  1) **Discord Quiz Bot** :
        - The bot should display 10-20 available quizzes for users to choose from, with each quiz consisting of multiple-choice questions.
        - Once a quiz is selected, the bot presents each question one by one, with a set timer (e.g., 30 seconds per question). The bot will track the time users take 
         to answer each question
        - After the quiz, display a leaderboard ranking players.The leaderboard should display users ranked by their points (total number of correct answers). If 
          multiple users have the same points, the ranking should be decided based on time taken per question (faster users rank higher). 
        - The leaderboard should show the top 10 players and the user’s rank, even if they are not in the top 10.
       
  2)  **Quiz Management application**:
      - Create a web-based CRUD application (Create, Read, Update, Delete) to manage quiz sets and individual questions.
      - Through this panel, authorized admins can create quiz sets (e.g., 10 questions per set), update quiz sets or individual questions, and delete existing sets 
         or questions. Admins can also view all quiz sets and questions.
      - The CRUD application will be connected to the same database that the Discord quiz bot uses, ensuring real-time synchronization of changes made in the admin 
        panel with the questions displayed to users during quizzes.

### Bonus Features:
1. Enhance the quiz management application by integrating  Large Language Models (LLMs) through APIs like OpenAI (ChatGPT) or Gemini to generate quiz question sets. This feature allows admins or question setters to specify the number of questions needed (e.g., 10 questions per quiz), and the AI should generate that number of questions.The generated questions should be editable, allowing admins to review and modify any of the AI-generated questions before finalizing the quiz set.
2. Deploy the Discord Quizbot on a cloud platform (e.g., Heroku, AWS, or Vercel) so it can run continuously and be accessible to users.

### Useful resources:
- [Build a Discord Bot With Python](https://betterprogramming.pub/coding-a-discord-bot-with-python-64da9d6cade7)
- [Build a Discord Quiz Bot](https://python.plainenglish.io/build-discord-quizbot-with-python-and-deploy-1-44dec1250a37)
- [Gemini API](https://ai.google.dev/)
- [Supabase](https://supabase.com/)
- [Building a CRUD App with Supabase and Express](https://medium.com/@heshramsis/building-a-crud-app-with-supabase-and-express-a-step-by-step-guide-for-junior-developers-81456b850910)
- [MongoDB](https://www.mongodb.com/) or [PostgreSQL](https://www.postgresql.org/)
  
### Tips
1. Use any language, technology, or framework of your choice to build the bot and backend.
2. Start with quiz selection, timing, and leaderboard display before adding extra features.
3. Use Gemini API for integrating LLMs for making questions ,as its API is free to use.
4. Ensure intuitive commands, similar to MEE6, and add slash commands for easy interaction.
5. Any useful additional/interesting feature will have bonus points.

