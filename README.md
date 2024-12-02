1. Speech-to-Text & Translation App:

- This project is a speech-to-text application that transcribes both live and recorded audio in its detected language, then translates it to English.

2. Project Description:

- Purpose:
  - This Speech-to-Text and Translation App is designed to provide seamless transcription and translation capabilities. This app uses advanced models and libraries to detect the language of the input audio, transcribe the speech, and translate it into English as a common language. It supports both live and recorded audio inputs.
    - It also keeps a history of processed audio along with the transcription, detected language, confidence score, and translation, which can be shown or hidden by the user.
      The project also enables the storage of this history in a CSV file for further analysis.

- Technologies Used:
  - OpenAI’s Whisper: Used for speech-to-text transcription.
  - fastText: Used for language detection.
  - Helsinki-NLP: Used for translation into English.
  - Torchaudio for audio processing.
  - Gradio: Used to create an practical interface.

- Challenges faced include:
  - Handling various audio file formats and resampling them to the required sample rate.
  - Optimizing the performance of language detection and translation on large audio files.
  - Working with new models to achieve live audio processing.

- Improvements might include:
  - Expanding translation support for more languages.
  - Enhancing the user interface with additional features, such as audio playback.
 
3. How to Run the Project:
- Clone the repository; replace your-username and your-repository with your GitHub username and repository name, respectively.

      git clone https://github.com/your-username/your-repository.git

      cd your-repository
- Set up dependencies; simply upload or open the notebook directly in Google Colab, as no installation is needed.
- Open your Google Colab notebook; use on your own from there.
  
4. How to Use the Project:
- In Google Colab, open your own notebook or upload it to your Google Drive.
  - Follow the provided instructions and run the cells sequentially.
- As or if needed, feel free to modify the input parameters and data. Be sure to adjust any file paths for local setups or if using Google Drive in Colab.
  - For additional information and or help, first refer to GitHub Docs then see documentation within this repository and README.
    - https://docs.github.com/en
5. Credits:
- This project was developed by Aiden C., using the resources listed here.
  - Whisper Model: OpenAI's Whisper for speech-to-text transcription via Hugging Face.
  - fastText: fastText for language detection via Hugging Face.
  - Helsinki-NLP: Helsinki-NLP Models for translation via Hugging Face.
  - Gradio: Gradio for creating the interactive web interface.
  - Torchaudio: Torchaudio for audio loading and processing.
- This project is licensed under the MIT License.
