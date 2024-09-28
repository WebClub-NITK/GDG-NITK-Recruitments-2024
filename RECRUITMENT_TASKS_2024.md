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
| [TravelTribe](#task-id-traveltribe)                            | Medium/Hard     |
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


## Task ID: TravelTribe

#### `Web/Mobile/Desktop Application`, `Google Cloud Platform`

Mentors: [Shreesha M](https://github.com/ShreeshaM07) ([+91 8310992995](https://wa.me/8310992995)), [Abhishek Satpathy](https://github.com/AbhishekSatpathy4848) ([+91 7619503901](https://wa.me/7619503901))

Difficulty: `Medium/Hard

### Description

Develop a comprehensive web or mobile application that enables users to create travel groups with friends, where the group owner selects a destination city or country. The app will utilize Gen AI APIs (such as the Gemini free tier) to generate customized travel itineraries based on user inputs, including travel dates and preferences(assume necessary details). It will allow group members to collaboratively modify the generated itinerary, and once finalized, it will sync with all group members' Google Calendars.

_Connect, Plan, and Go!_

Follow the steps below to complete this challenge:

1. Creation of an app or website with Authentication and Login of users.
2. Allow users to form groups.
3. Use any Gen AI API preferably Gemini to generate an itinerary based on the inputs like destination and dates of travel.
4. Allow the group members to Edit the Itinerary.
5. Update the Itinerary to the Google Calendars of the members.

Bonus Feature ( Optional ):

_Implementing the bonus features will make the task count as `Hard`, otherwise it will be `Medium`_
1. Allow for editing itinerary in realtime.
2. Expense management feature which tracks expenses during the travel and calculates the debt/credit of each group member.


### Useful resources:

- [ReactJS](https://react.dev/)
- [NodeJS](https://nodejs.org/en)
- [Flutter](https://docs.flutter.dev/)
- [Flask](https://python-adv-web-apps.readthedocs.io/en/latest/flask.html)
- [Firebase Auth](https://www.freecodecamp.org/news/use-firebase-authentication-in-a-react-app/)
- [Google Calendar in Python](https://medium.com/@ayushbhatnagarmit/supercharge-your-scheduling-automating-google-calendar-with-python-87f752010375)
- [Gemini in Flutter](https://medium.com/@blshashank59/integrating-the-gemini-api-in-your-flutter-application-9e767d578a5e)
- [Groups on Flutter](https://www.cometchat.com/docs/ui-kit/flutter/groups)
- [Google AI Studio](https://ai.google.dev/aistudio)

### Tips

1. Build the basic website/app with the Login using React.js/Flutter.
2. Have a neat UI where the owner can input details like start location, destination, dates of travel, duration and any other relevant details.
3. Integrate the Gemini API/any other Gen AI to create itinerary.
4. Add feature that allows users to make groups and allow members to edit the itinerary.
6. Explore about the realtime editing feature.
7. Then after things are decided by the group members update the itinerary to the google calendars of all group members.
8. Work on the expense management feature in case of the groups.

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