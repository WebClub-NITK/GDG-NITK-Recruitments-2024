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
| [Example Task](#task-id-example-task)                       | Medium     |
| [Emojify](#task-id-emojify)                                 |Easy/Medium |
| [Linkhub](#task-id-linkhub)                                 | Easy       |


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


## Task ID: Linkhub

#### `Web Application`

Mentors: [Apoorva Agrawal](https://github.com/imApoorva36) ([+91 8197404580](https://wa.me/8197404580)), [Mardav Gandhi](https://github.com/marcdhi) ([+91 9033398366](https://wa.me/9033398366))

Difficulty: `Easy`

### Description

Develop a web application called LinkHub that helps NITK students create personalized landing pages to organize and share important academic, club, and social links. This tool can be used for various purposes like sharing links for group projects, showcasing club activities, organizing research work, or preparing for placements. Each student will have their own customizable landing page where they can organize their links efficiently.

Follow the steps below to complete this challenge:

1. Build a clean, minimal user interface where users can add, edit, and delete links
3. Allow students to customize the appearance of their landing page, including themes and NITK-branded backgrounds (e.g., college colors, logos)
4. Enable students to categorize their links (e.g., Projects, Clubs, Research, Social Media) and assign custom titles to each link
5. Ensure that the links open in a new tab when clicked

Bonus Feature ( Optional ):

1. Each student's page should have a custom shareable URL, for example, `<your_domain>.vercel.app/username` or `<your_domain>.netlify.app/username`, making it easy to share with others
2. Searchable Links: Implement a search feature that allows students or visitors to quickly find specific links on the landing page.

### Expected Input and Output Examples:

`Input: User provides links (e.g., Instagram, LinkedIn, personal website) and customizes their page's appearance.`

Output: "A personalized landing page with clickable links that can be shared with others."

### Useful resources:

- [HTML and CSS Basics](https://www.w3schools.com/html/)
- [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Github Pages](https://docs.github.com/en/pages)
- [Vercel documentation](https://vercel.com/docs)
- [Netlify documentation](https://docs.netlify.com/)

### Tips

1. Focus on Usability: Since the app is for students, prioritize a simple and intuitive UI where adding and managing links is effortless.
2. Responsive Design: Ensure that the page looks good on mobile, as many users will view it on their smartphones.
3. Styling Libraries: Consider using CSS libraries like Bootstrap or Tailwind CSS to speed up development and make the UI more visually appealing.
4. Local Storage: Implement local storage so users can save their links and page settings locally if authentication is not part of the scope.
5. Custom Slugs: Use URL slugs (<your_domain>.vercel.app/username) to make the page unique and easy to share.
<!-- add more here -->


