# Voice_clone
A voice clone AI model made using Machine Learning and Deep Learning.
The provided code performs voice cloning using the Tortoise TTS library. Here's a summary of what the code does:

Install Dependencies: The code installs required Python packages like scipy, tortoise, transformers, and huggingface_hub using pip3. It then clones the Tortoise TTS repository from GitHub and installs its dependencies.

Initialize Text-to-Speech Model: The code imports necessary libraries and initializes the TextToSpeech model from the Tortoise TTS library.

Generate Synthetic Voice Using Pre-trained Model: It generates synthetic speech using a pre-trained voice model (train_dotrice). The model converts the input text ("Hey there, nice to meet you!") into speech, attempting to mimic the voice of the specified speaker.

Save and Play the Generated Speech: The generated speech is saved as an audio file named 'generated.wav'. The IPython library is used to play the audio and provide an audio preview in the Colab notebook.
