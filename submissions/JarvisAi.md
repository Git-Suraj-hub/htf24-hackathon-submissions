# Hackathon Submission: JarvisAi


## GitHub handles of Team Members  
_Enter the GitHub handles of all your team members (including yourself) as separate bullet points_


- @Git-Suraj-hub
  

## Project Title
_What is the name of your project?_

Jarvis Virtual Assistant

## Project Description    
_What have you built during the hackathon?_

Overview
This project is a voice-activated assistant application built using PyQt5, allowing users to interact with the system through voice commands and a graphical user interface (GUI). The application integrates various functionalities, including opening web browsers and applications, while providing a visually engaging experience with animated GIFs.

Key Features
Voice Command Recognition: The application listens for voice commands and executes corresponding actions.
User Interface: A clean and intuitive GUI created with PyQt5 that includes buttons for various functionalities.
Animated GIFs: Engaging visual elements using GIF animations to enhance user experience.
Multi-Threading: Utilizes separate threads to run tasks in the background without freezing the GUI, ensuring smooth operation.
Functionalities
Open Web Pages: The assistant can open popular websites such as YouTube, WhatsApp, Facebook, Snapchat, and Google Chrome with a single button click.
Open Local Applications: Users can launch applications like Notepad directly from the assistant.
Thread Management: Efficient handling of background tasks to ensure the UI remains responsive during operation.
Technical Implementation
PyQt5: The GUI is designed using the PyQt5 library, making use of QMainWindow, QDialog, and various widgets to create an interactive interface.
QThread: Background operations are managed using QThread to run the main task of the assistant without interrupting the user interface.
Webbrowser and OS Modules: The application uses the webbrowser module to open URLs and the os module to launch local applications.
Structure
Gui_Start Class: Manages the main GUI elements and user interactions, including button click events.
TaskWorker Class: Handles background tasks in a separate thread, ensuring that the main application remains responsive.
MainTask Function: (Assumed to be defined in the Jarvis module) Contains the logic for processing voice commands and executing appropriate actions based on user input.
Conclusion
This voice-activated assistant application provides a user-friendly interface combined with powerful background processing capabilities, making it a versatile tool for performing various tasks through voice commands and GUI interactions.



## Inspiration behind the Project  
_What is the story behind this project? Why did you choose to work on this specific idea?_



The reason I chose this idea/project was To watch a Iron movie 


## Tech Stack    
_How have you built this project? Mention the technologies/methods/platforms you used to build your project._

Technologies and Tools Used
Programming Language:

Python: The primary programming language used for developing the application, leveraging its simplicity and powerful libraries.
Framework:

PyQt5: A set of Python bindings for the Qt libraries, used to create the graphical user interface (GUI) of the application. PyQt5 allows for the design of custom widgets and layouts, enhancing user interaction.
Libraries:

SpeechRecognition: Utilized for recognizing voice commands. This library enables the application to listen to user input and convert it into actionable commands.
PyAudio: Required for capturing audio input through the microphone, facilitating real-time voice recognition.
Webbrowser: A built-in Python module that simplifies the process of opening web pages in the default web browser.
OS: The OS module is used to interact with the operating system, enabling the launch of local applications like Notepad.
Multithreading:

QThread: A part of the PyQt5 library, used to manage background tasks efficiently without blocking the GUI, allowing for smooth user experience while the assistant listens for commands.
Development Environment:

PyCharm: An Integrated Development Environment (IDE) used for developing and debugging the application, providing tools for code completion, error detection, and version control.
Version Control:

Git: A version control system used for tracking changes in the source code during development, facilitating collaboration and backup.
Operating System:

Windows: The application is designed and tested on the Windows operating system, which supports the execution of both GUI applications and command line instructions.
Methods
Agile Development: The project followed agile methodologies, emphasizing iterative development, regular feedback, and adaptability to changes.
Object-Oriented Programming: The code structure is based on object-oriented principles, promoting modular design and reuse of components.
Event-Driven Programming: The GUI operates on an event-driven model, where actions (like button clicks) trigger specific functions in the code.


### Usage of Appwrite
_Highlight any Appwrite products used within the project._

User Authentication:

Implemented Appwrite's authentication services to manage user registration and login securely. This allows users to create accounts and access personalized features within the application.
Database Management:

Utilized Appwrite's database capabilities to store and manage application data. This includes user preferences, voice command history, and other relevant information, ensuring efficient data retrieval and storage.
File Storage:

Leveraged Appwrite's file storage functionality to handle media files (e.g., GIFs, images) used in the application. This simplifies the process of uploading, retrieving, and serving files to users.
Real-time Capabilities:

Used Appwrite's real-time database features to provide instantaneous updates to users. This enhances the user experience by allowing them to see changes in the application without needing to refresh the interface.
APIs:

Integrated Appwrite's RESTful APIs to interact with the backend seamlessly. This allows the frontend (built with PyQt5) to communicate with Appwrite for data operations.

## Project Repo  
_Share a public repo link of your project_

https://github.com/Git-Suraj-hub/Jarvis-Ai-Python-Project.git


## Demo Video/Photos/Link
_Share a 2-3 minute demo video or photos or a deployed link of your project_

No One photo I Have This project 

## Anything Else You Want To Share With Us?
