VisioVoice : Assistant for blind
This voice assistant is designed with a primary focus on improving the quality of life for individuals with visual impairments. It offers a range of customized functionalities and employs speech-to-text technology to assist users in accessing essential features. In essence, it serves as a dedicated chatbot tailored to meet the unique needs of the visually impaired community.

Fetaures which make "VisioVoice" unique:
The system comprises wearable headphones connected to a Logitech webcam, which is in turn interfaced with a Raspberry Pi. It operates by interpreting user input in the form of speech and, in response, provides spoken feedback while executing various tasks.

Key Features:

Description:

VisioVoice provides a concise summary of the immediate surroundings.
Under the category of "Road Conditions," VisioVoice offers a comprehensive assessment to assist visually impaired users.
VisioVoice is capable of identifying and specifying familiar locations, such as classrooms, kitchens, and bedrooms.
The system responds by indicating the quantity of individuals, objects, and more within the webcam's frame.
Find:

VisioVoice resonds to commands like find my purse?, check if my watch is in this room? depending upon whether @Entity is present in the frame of the camers
Read:

VisioVoice also detects text from images and reads it loud.
As a further application it can summarize articles from newspapers.
Fill forms

VisioVoice also reads out forms (majorly applicable for bank purposes)
Mobile Interactions

It can read out notifications from mobile and as a further application respond to messages, emails, calender, etc
Tech- stacks used:

1. SpeechRecognizer, Google API for speech to text conversion

2. Python Text to Speech https://pypi.org/project/pyttsx3/

3. Object Recogniiton using COCO Dataset

4. Google Cloud Vision API 

5. Dialogflow
Install Dependencies Download the credential for Google Vision API. Copy and paste the files at thr required position.

   git clone https://github.com/Ajaysai2001/VisioVoice_Assistant-for-blinds.git
   cd DobaraMatPuchana
   pip install -r requirements.txt
Run Code:

python main.py
