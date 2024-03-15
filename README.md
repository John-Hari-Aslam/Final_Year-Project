This Streamlit application, titled "HandScribeVoice", allows users to draw text on a canvas, recognize the handwritten or drawn text, and convert it into speech. Here's a breakdown of its functionality:

Drawing Canvas: Users can draw text on a canvas provided within the application interface.

Text Recognition: After drawing text, users can click the "Recognize Text" button to initiate the recognition process. The application utilizes the EasyOCR library to recognize the text from the drawn image.

Voice Conversion: Once the text is recognized, it is displayed to the user, and an image related to the recognized text is fetched from Google Custom Search API. Additionally, the recognized text is converted into speech using the Pyttsx3 library, with options to select the voice gender (male or female).

Customization: Users can customize the voice gender by selecting either male or female before converting the recognized text into speech.

External APIs: The application integrates with external APIs, including EasyOCR for text recognition and Google Custom Search for fetching related images.

User Interface: The user interface is designed using Streamlit, allowing for easy interaction with the drawing canvas and voice conversion features. The sidebar provides options for voice gender selection and initiating the text recognition process.

This application can be used for various purposes, such as assisting individuals with visual impairments in converting handwritten notes into speech, generating audio content from handwritten messages, and experimenting with text recognition and speech synthesis technologies.

To run the application:

Install the required libraries mentioned in the code (Streamlit, PIL, easyocr, pyttsx3, streamlit_drawable_canvas, and requests).
Replace the placeholders for api_key and cx with your Google Custom Search API key and custom search engine ID.
Execute the script in your Python environment using streamlit run filename.py.
