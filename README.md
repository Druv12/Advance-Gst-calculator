Project Report: GST Calculator with Voice Interaction

Vision of the project:
This project aims to develop an interactive voice-enabled GST calculator, which will help users to calculate GST for foreign and Indian products with ease and speed. The application uses a speech recognition interface for taking voice input from the user and processes the response with the aid of text-to-speech technology for providing back the results to the user. It incorporates a currency conversion feature that aids foreigners in calculating GST in USD, which is then changed to INR.

Technologies Used:
Speech Recognition (speech_recognition): It receives the input from the user by voice.
Text-to-Speech (pyttsx3): The output is communicated back to the user verbally.
Standard Libraries of Python: It provides the basic logic and calculations.

Key Features:
Voice-based Input and Output:

The user can give instructions entirely by voice in the system.
The system will return further confirmation in a female voice (via pyttsx3), making the interface friendlier.

Currency Conversion:

The input for foreigners (those from outside India) is USD as currency ; the system will convert the amount back to INR, using a fixed conversion rate of 3.5.

GST Calculation for Indian and Foreign Users:

Users can input the category under which they want to calculate GST.
The categories include:
Essentials (0% GST)
Needs (5% GST)
General goods (12% GST)
Vision goods (18% GST)
Luxury Goods and Sin Goods (28% GST)
For invalid input, the app checks and the user has an opportunity to re-enter their data. 
