# BOTAnshul
Live Demo : https://anshulp2912.github.io/

## Rise of Chatbots 	:robot:
Chatbots radically alter the way organizations communicate with consumers, execute lead generation projects, and simplify payments. In the future, more and more brands are going to develop apps. Bots can gather and interpret data in order to take critical decisions. Bots are used to streamline personal tasks, such as exercise, childcare, infants, e-learning, etc or everyday activities.

Via varied market roles and user apps, chatbots are going to the mainstream. Moving forward, automation will make its origins ever deeper and solve all of the company's chatbot issues. Your customer path and engagement can be profoundly influenced by a deep awareness of the company needs and the subsequent introduction of bots.

In conclusion, the most creative approach for bridging the divide between technology and education has turned out to be chatbots.

## Resume Chatbot :bookmark_tabs:
The basic one page word document description has become boring (wasn't it ever?). Perhaps it is time to please some future employers by developing a bot version of yourself to clarify your accomplishments for you.

My intention was to explore the Chatbot world and build something simple, so I thought I would address a topic I know which is me! 

In the last decade, LinkedIn profiles haven't changed much. They are more appealing than resumes, of course, but they are not any more engaging. In reality, it's just a compilation of dates, names, and buzzwords, which is great for weeding out 90% of applicants. But how can you tell anyone if someone is looking for a career once you've found an attractive candidate? How are you going to decide if someone is perfect fit? What if you would like to see samples of the job they do? 

At this point of the recruiting process, I thought a bot should step in because bots can answer repeated questions quickly (let's face it: recruiters all essentially ask the same things). For line items on a resume, Bots may also provide more meaning to provide a sense of the personality of someone.

I think bots might deliver convincing introductions to a human in the not-too-distant-future, not only for career recruiting, but for something. For example, dating sites have started making users fill up some QA's through which someone else can talk to their BOT when they are offline.

## BOTAnshul - ResumeBOT
### What do you need??
- Python 3.6/3.7
- RASA

### What and Why about RASA?
The RASA stack is an open-source AI tool which is simple to configure as an open source system. In reality, consumers do not choose to share their data in certain instances, because most of the available resources are cloud-based and offer information as a service. In your environment, you can not run them internally. So you must give the details to a third party. For RASA, no such problem remains. With full control over it you can create, distribute or host Rasa internally on your server or environment.

RASA is made up of two core components :
- Rasa NLU : a library for natural language understanding (NLU) which does the classification of intent and extract the entity from the user input and helps bot to understand what the user is saying.
- Rasa Core : a chatbot framework with machine learning-based dialogue management which takes the structured input from the NLU and predicts the next best action using a probabilistic model like LSTM neural network.

### Getting Started with RASA
There are few important keywords tht one must know before creating a chatbot:
- Intent — Intent is nothing but what is targeted at by the consumer. 
- Entity — The entity is used to derive valuable information from the input of the user. 
- Stories — In terms of intent and action taken by the bot, stories describe the sample conversation between the user and the chatbot. 
- Actions — Actions are essentially the bot's activities, either asking for some more specifics to get all the entities or integrating with some APIs or asking the database to get/save some stuff.

Documentation for RASA : [Documentation](https://rasa.com/docs/)
RASA files for BOTAnshul: [Link](https://github.com/anshulp2912/BOTAnshul/tree/main/source)

### PROJECT FLOW STRUCTURE
![project-flow](https://github.com/anshulp2912/BOTAnshul/blob/main/media/BOTAnshulPipeline.jpg?raw=true)

### Gallery :camera_flash:
Image Library of Chatbot in Custom UI : 

### Things left to do :alarm_clock::
:x: Contact Intent

:x: Extracurricular Activities Intent

:x: Research Intrest Intent

:x: Resume Download Intent

:x: Personalize the responses using custo GIFs

:x: BOT initiates the chat

### Acknowledgement
- https://rasa.com/docs/
- https://itsromiljain.medium.com/build-a-conversational-chatbot-with-rasa-stack-and-python-rasa-nlu-b79dfbe59491
- https://medium.com/the-mission/how-i-turned-my-resume-into-a-bot-and-how-you-can-too-f03847352baa
