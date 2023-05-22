# Proton+

Welcome to the Medical Services Chat Bot! This chat bot provides a range of medical services to users, including hospital appointment booking, nearby hospital search, medicine recommendation, and more. The application is built using Flutter for the frontend and Python for the backend AI models.


## Features

 - **Hospital Appointment Booking:** Users can easily book appointments with hospitals through the chat bot. The chat bot will guide them through the process, asking for relevant information such as preferred date, time, and reason for the appointment.

 - **Nearby Hospital Search:** Users can search for nearby hospitals based on their location or a specific address. The chat bot utilizes location services and provides a list of hospitals in the vicinity, along with details such as contact information, ratings, and user reviews.

 - **Medicine Recommendation:** Users can get personalized medicine recommendations based on their symptoms, medical history, and other relevant factors. The chat bot utilizes AI models to analyze the user's input (in the form of prescription) and provides accurate and helpful recommendations.

 - **General Medical Information:** The chat bot can provide general medical information on various topics such as common ailments, preventive measures, first aid, and healthy living tips. Users can ask questions and receive reliable information from trusted sources.

 - **Emergency Assistance:** In case of emergencies, the chat bot can provide immediate assistance by providing contact numbers for emergency services or guiding users on basic first aid procedures until professional help arrives.
 
 - **User Account Integration:** Users can create accounts and log in to the chat bot to access personalized features, such as storing their medical history, appointment records, and receiving reminders for upcoming appointments or medication schedules.
 - **Natural Language Processing (NLP):** The chat bot utilizes AI models and natural language processing techniques to understand user queries, provide appropriate responses, and improve over time through machine learning.



## Technologies Used

- **Flutter:** The frontend of the application is developed using the Flutter framework, which enables cross-platform compatibility and a smooth user interface.

- **Python:** The backend of the chat bot is built using Python, which includes AI models for natural language processing, recommendation systems, and data analysis.

- **AI Models:** The chat bot leverages various AI models, such as NLP models for understanding and generating human-like responses, recommendation systems for medicine suggestions, and data analysis models for extracting insights from medical records.

- **APIs and Libraries:** The application integrates with various APIs and libraries to fetch hospital information, process location data, send notifications, and handle user authentication and data storage.
## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Hospital Search API` | `string` | **used for the nearby hospital search feature**. Your API key |
| `Location Services API` | `string` | **used for providing accurate nearby hospital search results**. Your API key |
| `Notification Services API` | `string` | **handles the delivery of notifications to the intended recipients**. Your API key |





## Setup Instructions


To run the Medical Services Chat Bot project locally on VS Code, follow these steps:

 - Clone the project

```bash
  git clone https://link-to-project
```

- Go to the project directory

```bash
  cd my-project
```

- Open VS Code and navigate to the project directory.

 - Ensure that you have Flutter and Dart SDK installed on your system. If not, follow the Flutter installation guide: Flutter Installation Guide(https://docs.flutter.dev/get-started/install)

- Install the required VS Code extensions for Flutter and Dart. Open the Extensions view in VS Code (Ctrl+Shift+X), search for "flutter" and "dart", and install the respective extensions.

- Set up a virtual environment for Python using a package manager like pipenv or other. Activate the virtual environment.

- Install the required Python packages by running the following command in the terminal:


```bash
  pip install -r requirements.txt
```

- Open the lib/main.dart file in VS Code. Make sure you have a compatible device connected (physical device or emulator) for running the Flutter application.

- Start the Flutter application by clicking on the Run button in the VS Code toolbar or by running the following command in the terminal:

```bash
  flutter run
```

This will launch the application on the connected device or emulator.

- In a separate terminal, navigate to the Python backend directory (backend/) and run the following command to start the backend server:

```bash
  python app.py
```

This will start the backend server on the default port or the specified port.

- Once both the Flutter application and the Python backend server are running, you can interact with the our Chat Bot locally by opening the app on the device or emulator.

Please note that you might need to configure the necessary environment variables, API keys, and database connection details as mentioned in the previous sections, depending on your local setup.

Ensure that you have the appropriate dependencies installed and the correct configuration in place to run the project successfully.

## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Blue | ![#0a192f](https://via.placeholder.com/10/00B5e2?text=+) #00B5E2 |
| White | ![#00d1a0](https://via.placeholder.com/10/fff?text=+) #ffff |

The Medical Services Chat Bot follows a blue and white color scheme for its user interface. The choice of colors is based on the following reasons:

- Blue: Blue is often associated with trust, reliability, and professionalism, which are crucial attributes in a medical services application. It instills a sense of confidence and calmness in users when interacting with the chat bot for their healthcare needs.

 - White: White represents cleanliness, purity, and simplicity. It enhances the readability of text and other visual elements, ensuring that information is presented clearly to users. The white background also promotes a clean and clinical aesthetic, aligning with the medical context of the application.
## Screenshots

Here are a few screenshots from the Our Chat Bot application:

**Description of the screenshot**

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

**Description of the screenshot**

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

**Description of the screenshot**

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

**Description of the screenshot**

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)



## Demo

To experience a live demo of the our **proton+** Chat Bot, you can visit our website **//demolink**. The demo allows you to explore the features and functionalities of the chat bot in a simulated environment.


## Team Members

Our Chat Bot project is a collaborative effort by a team of dedicated individuals. Here are the team members who contributed to the development of the application:

- [@AdarshaHalder](https://github.com/AdarshaHalder)

- [@anik0810](https://github.com/anik0810)

- [@sanmay321](https://github.com/sanmay321)

- [@arka](https://www.github.com/arka)

- [@swarnajha](https://github.com/swarnajha)
## License

Our Chat Bot is licensed under the [MIT](https://choosealicense.com/licenses/mit/)


## Contact

For any questions or enquiries, please contact us at [adarshahalder02@gmail.com]

We appreciate your interest in the Our Chat Bot. Thank you for using our application and providing valuable feedback for improvement!
