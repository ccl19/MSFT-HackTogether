# MSFT-HackTogether
Nexus-AI focussed submission

# What is our product?
Our submission is a teams tab application that links to our website focusing on student productivity.
We have implemented Microsoft OpenAI in a variety of places in our design in ways that cut down on the time spent by students in their day-to-day life.
Our submission is focussing on the Application Tracker, the File Summarizer and the ToDo Chatbot sections of Nexus as they are the key areas where AI has been implemented to high usage.

# Application Tracker



# File Summarizer
Our File Summariser uses Microsoft Graph so you can choose any file (including Word, PowerPoint, PDF, etc) to upload from your OneDrive, alternatively you can upload a PDF file from your local files. It then accesses the Azure OpenAI to pass the text from the file in small chunks via a custom prompt to effectively summarise the file for academic use. This ensures the summary is still detailed enough for a university student to be able to learn what the slides are about, while still being concise enough for the summary to be more effective to read than the original slides. From here there is also the option to upload the summary to a new section in Microsoft OneNote so the student can efficiently incorporate the summary to the rest of their notes for easy revision purposes.

# Chatbot
We have integrated Azure OpenAI into a chatbot which allows users to have a seamless interaction with a safe AI. We have included buttons which allow shortcuts within the chatbot. Creating a to-do list is easy when using the chatbot, simply type your plans for the day and allow our AI to help with timings and conveniently add them to your Microsoft Todo App. Another shortcut includes automatically displaying the weather in the user's location, our chatbot uses Weather APIs to retrieve weather information depending on the IP address location of users. 
