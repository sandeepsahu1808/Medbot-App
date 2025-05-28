# Welcome to MedBot!

👥 Team: Sandeep Sahu, Zaid Shaikh, Aditi Pal, Dibyas Dubey

This documentation is intended to assist both new and returning users in setting up the MedBot application on their local development environment. It covers installation, configuration, running the app on an Android emulator or device, interacting with its AI-driven features, and troubleshooting common issues. Whether you are exploring MedBot for the first time or need a concise refresher, this guide provides comprehensive instructions for every step of your experience.

## AI-Powered Medical Assistant App
MedBot is an AI-powered Android application that provides users with intelligent health advice and medical
assistance through natural language conversation. The app allows users to describe symptoms or ask
health-related questions in plain language, and leverages advanced natural language processing (NLP) and
machine learning techniques to interpret these inputs. Based on the query, MedBot generates contextual
responses, suggesting possible conditions and recommended next steps. This project highlights proficient
use of modern Android development tools and AI services to create a practical, user-friendly healthcare
assistant.

## Key Features
1. AI Chatbot (Symptom Analysis): Interactive chat interface where users describe symptoms in free
text. The AI processes these inputs using NLP and provides explanations of possible conditions or
issues.

2. Medical Information Retrieval: Leverages external medical APIs or a local knowledge base to fetch
accurate, up-to-date health data and guidelines. Ensures that the advice and information provided
are reliable.

3. Real-Time Suggestions: Offers immediate, context-aware health tips and next steps (e.g., home
care advice or when to consult a doctor) based on the current conversation. Responses are
generated on-the-fly for a smooth experience.

4. User-Friendly Interface: Clean and intuitive Android UI built with Material Design components. The
interface is responsive and easy to navigate, ensuring users can interact with MedBot effortlessly.



## Technology Stack
1. Android (Java/Kotlin): Native platform and languages used for building the MedBot application.

2. Android Studio & Gradle: Development IDE and build automation tools used for project setup,
compilation, and dependency management.

3. OpenAI GPT (Optional): Integration with OpenAI’s GPT language model via API for generating
advanced, conversational responses.

4. Firebase (Optional): Cloud backend services such as Firestore database and Authentication for user
data management and scalability. 

## System Requirements

🛠️ To run this application, the following operating systems are required: Windows 11 (for Windows users), or the latest version of MacOS (Sequoia 15.1.1 for Apple users), which supports both Intel and Apple Silicon processors.

- Android device or emulator running Android 8.0 (API level 26) or above

- Android Studio (latest stable release)

- OpenAI API key for GPT integration, or access to an alternative medical knowledge base

- Optional: Firebase account for user authentication and data storage
## Setup & Installation
- Clone the repository:git clone https://github.com/sandeeps2004/MedBot.git
  
- Open in Android Studio:Launch Android Studio and select File > Open, then navigate to the cloned MedBot project directory.
  
- Resolve Dependencies: Ensure you have the required Android SDK installed. Android Studio should automatically sync the Gradle project and download any necessary libraries.
  
- Configure API Keys (if applicable):For OpenAI GPT integration, add your OpenAI API key to the project (e.g., in a secure local.properties or resource file).
  
- For Firebase, place the google-services.json config file in the app/ directory and add your Firebase credentials.
  
- Build and Run:Connect an Android device or start an emulator. Use Run > Run 'app' in Android Studio to build and install the MedBot application on your device. After setup, the project will compile and launch on the selected device. You can then interact with MedBot through the chat interface.


## Quick Start

1. Launch MedBot: Open the app on your Android device.

2. Enter a Query: In the chat field, type your symptoms or a health-related question (e.g., “I have a
sore throat and fever”).

3. Send Request: Tap the Send button. MedBot’s AI assistant will process your input.

4. Review the Response: The app will display a response explaining possible conditions, advice, or
next steps based on your query. 

5. Continue the Conversation: You can ask follow-up questions or provide additional details (e.g.,
“What should I do next?”) to refine the advice.

6. Important: The information provided by MedBot is for informational purposes only and is not a
substitute for professional medical advice. Always consult a qualified healthcare provider for
serious or urgent medical concerns.



## Result
![image](https://github.com/user-attachments/assets/c5de4f26-655e-41ca-aaed-e7dbb25c2e54)
![image](https://github.com/user-attachments/assets/d279c9a5-7cae-4d88-842a-ee170534a7c3)
![image](https://github.com/user-attachments/assets/9ce9f7a3-ab57-406a-a2cc-a6c62cbb9b3a)


##  Troubleshooting

‼️ If you experience any technical issues or unexpected behavior while using MedBot, ensure that the application has been correctly installed and that all necessary permissions are granted on your Android device. Try restarting the app or the device to resolve minor glitches. For persistent issues, verify your internet connection, as MedBot relies on a stable network for real-time AI responses.
If the problem continues, reinstall the application to ensure the latest version is running. In case of errors related to voice input or chatbot interaction, check whether your microphone access and device language settings are correctly configured. For further assistance or to report a bug, feel free to comment,We value user feedback and are committed to improving MedBot’s functionality and user experience.



## Thank you so much for choosing Medbot!







  
