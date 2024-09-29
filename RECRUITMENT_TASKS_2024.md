# Tasks

- It is perfectly fine if you have no experience in the field and trying it out for the first time. Please put in sincere efforts and try to learn from whatever you complete!
- Each Task has an ID, tags, mentor, description, tips and useful resources
- You can refer to the resources put up in each task to understand the concepts required to complete the task.
- Feel free to reach out to the mentors for any assistance you need.
- Mention the Task ID attempted in the README of your private GitHub repository.
- Read the instructions, evaluation criteria and submission details [here](./README.md)

### Table of contents


| Tasks                                                               | Difficulty  |
| ------------------------------------------------------------------- | ----------- |
| [Emojify](#task-id-emojify)                                         | Easy/Medium |
| [Web-Based Diagram Generator](#task-id-web-based-diagram-generator) | Medium      |
| [Fast-Type](#task-id-fast-type)                                     | Medium      |
| [Competitive Programming Portal](#task-id-competitive-programming-portal) | Medium     |
| [TravelTribe](#task-id-traveltribe) | Medium/Hard     |

| InterSIG Tasks                                                      | Difficulty  |
| ------------------------------------------------------------------- | ----------- |
| [AgriVerify](#task-id-agriverify)                                   | Medium/Hard |


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

---

## Task ID: Web-Based Diagram Generator

#### Full-Stack Development, Diagram Generation, Graphviz

Mentors: [Udit Jain](https://github.com/UditJain2622004) ([+91 8708596606](https://wa.me/918708596606)), [Shubham Subodh Rasal](https://github.com/Shubham-Rasal) ([+91 7349784770](https://wa.me/917349784770))

Difficulty: `Medium`

### Description

Develop a web application inspired by `Mermaid.js` that enables users to generate various types of diagrams based on user input. Users can enter data or upload relevant files, and the system will produce the desired diagram. Focus on letting users generate diagrams with minimal input. The application should also provide the option to export the generated diagram in popular formats like PNG and PDF.

Some Popular Diagram Types your application _may_ support:

- Flowcharts
- ER Diagrams
- Class Diagrams
- Dependency Diagrams (for Node.js/React projects)

**Note :** The type and number of diagram(s) your application support is not fixed. You are free to implement support for any type and number of diagram(s). The diagrams given above are just some examples.

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

---

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

---

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
8. You can choose to implement a backend service to handle API requests and data processing.
9. Allow the user to add upcoming contests to his calendar.
10. Feel free to add any extra information from these platforms (heatmap, recent problem submissions, number of solved questions, difficulty of questions solved etc). Adding extra information would add bonus points.
    
### Useful resources:

- [Codeforces API](https://codeforces.com/apiHelp)
- [AtCoder API](https://atcoder-api-python.readthedocs.io/en/latest)
- [Unoffical Leetcode API](https://github.com/alfaarghya/alfa-leetcode-api)
- [NodeJS](https://nodejs.org/en)
- [Flask](https://flask.palletsprojects.com/en/3.0.x/)
- [Flutter](https://flutter.dev/)
- [React Native](https://reactnative.dev/)

### Tips

1. Any Mobile App Developement Technology can be used, either Native or Cross-Platform.
2. Start by exploring the different platform APIs and the information they deliver.
3. Then look into ways you can process and surface available information throught clean UI/UX.
3. In case you find platforms that don't provide API endpoints for contests, display other information available.
4. You can also use Unofficial Platform APIs, if official alternatives don't exist.

--- 

## Task ID: AgriVerify

#### `Web Application`, `Blockchain`, `Smart Contracts`

Mentors: [Krishna Tulsyan](https://github.com/krishna) ([+91 9506221135](https://wa.me/9506221135)), [Apoorva Agrawal](https://github.com/imApoorva36) ([+91 8197404580](https://wa.me/8197404580)), [Mardav Gandhi](https://github.com/marcdhi) ([+91 9033398366](https://wa.me/9033398366))

Difficulty: `Medium/Hard`

### Description

**AgriVerify**, where you'll blend blockchain technology with organic farming to bring trust and transparency to every crop grown! In this task, you’ll be creating a decentralized platform that empowers farmers to easily certify their organic produce and generate QR codes that consumers can scan for instant verification.

Imagine walking through a market, scanning a QR code on an apple, and instantly seeing its certification, the farm it came from, and the people behind it—all with the power of blockchain!

---

### Steps to Complete the Challenge:

1. **Farmer Onboarding:**  
   Build a welcoming system where farmers can easily sign up using wallet authentication and request certification for their crops. The process should be seamless, ensuring the user experience is as simple as organic farming itself.

2. **Certification Process:**  
   Dive into smart contracts! Implement a contract where farmers submit their crops for certification. For simplicity, assume the certifications are auto-approved. The goal is transparency and accessibility.

3. **QR Code Generation:**  
   Generate QR codes for certified crops. These codes should link to a beautifully simple page showing the certification details stored on the blockchain, enabling consumers to instantly trust their food.

---

### Bonus Task:

**Note**: Attempting this section will consider your submission as a `hard task`.

**Push Notifications:**  
Add an extra touch by integrating **[Push Protocol](https://push.org/)** to notify farmers in real-time when their crops are certified. Keep them excited and informed with instant updates!

---

### Useful Resources:
- [Hardhat Documentation](https://hardhat.org/getting-started/)
- [QR Code Generation with JavaScript](https://www.npmjs.com/package/qrcode)
- [Push Protocol Guide](https://push.org/docs/notifications/)
- [Push Protocol Tutorials](https://push.org/docs/notifications/tutorials/)
- [OpenZeppelin Contracts Wizard](https://wizard.openzeppelin.com/#) - Easily create custom ERC20 and ERC721 contracts
- [Solidity by Example](https://solidity-by-example.org/) - Learn Solidity with simple, practical examples
- [Web3.js Tutorial for Beginners](https://www.dappuniversity.com/articles/web3-js-intro) - Interact with smart contracts from the frontend
- [How to Build a Blockchain App with Ethereum](https://www.dappuniversity.com/articles/blockchain-app-tutorial) - Step-by-step tutorial on creating a dApp

---

### Tips:
- Focus on creating an easy-to-use platform where farmers feel confident certifying their crops.
- Use smart contract libraries like **OpenZeppelin** to ensure security and accelerate development.
- Keep the frontend user-friendly, ensuring a fun and smooth experience for both farmers and consumers.

---

## Task ID: TravelTribe

#### `Mobile/Desktop Application`, `Google Cloud Platform`

Mentors: [Shreesha M](https://github.com/ShreeshaM07) ([+91 8310992995](https://wa.me/8310992995)), [Abhishek Satpathy](https://github.com/AbhishekSatpathy4848) ([+91 7619503901](https://wa.me/7619503901))

Difficulty: `Medium/Hard`

### Description

Develop a comprehensive mobile application that enables users to create travel groups with friends, where the group owner selects a destination city or country. The app will utilize Gen AI APIs (such as the Gemini free tier) to generate customized travel itineraries based on user inputs, including travel dates and preferences(assume necessary details). It will allow group members to collaboratively modify the generated itinerary, and once finalized, it will sync with all group members' Google Calendars.

_Connect, Plan, and Go!_

Follow the steps below to complete this challenge:

1. Creation of an app with Authentication and Login of users.
2. Allow users to form groups.
3. Use any Gen AI API preferably Gemini to generate an itinerary based on the inputs like destination and dates of travel.
4. Allow the group members to Edit the Itinerary.
5. Update the Itinerary to the Google Calendars of the members.

Bonus Feature ( Optional ):

_Implementing the bonus features will make the task count as `Hard`, otherwise it will be `Medium`_
1. Allow for editing itinerary in realtime.
2. Expense management feature which tracks expenses during the travel and calculates the debt/credit of each group member.


### Useful resources:

- [Flutter](https://docs.flutter.dev/)
- [Firebase](https://firebase.google.com/)
- [Flask](https://python-adv-web-apps.readthedocs.io/en/latest/flask.html)
- [Firebase Auth](https://www.freecodecamp.org/news/use-firebase-authentication-in-a-react-app/)
- [Google Calendar in Python](https://medium.com/@ayushbhatnagarmit/supercharge-your-scheduling-automating-google-calendar-with-python-87f752010375)
- [Gemini in Flutter](https://medium.com/@blshashank59/integrating-the-gemini-api-in-your-flutter-application-9e767d578a5e)
- [Groups on Flutter](https://www.cometchat.com/docs/ui-kit/flutter/groups)
- [Google AI Studio](https://ai.google.dev/aistudio)

### Tips

1. Feel free to use any mobile app development technology, either Native or Cross-Platform.
2. You can implement a backend service using Flask or Node.js or use backend-as-a-service platforms like Firebase or Supabase.
3. Build the basic app with the sign up/in functionality.
4. Have a neat UI where the owner can input details like start location, destination, dates of travel, duration and any other relevant details.
5. Integrate the Gemini API/any other Gen AI to create itinerary.
6. Add feature that allows users to make groups and allow members to edit the itinerary.
7. Explore about the realtime editing feature.
8. Then after things are decided by the group members update the itinerary to the google calendars of all group members.
9. Work on the expense management feature in case of the groups.
