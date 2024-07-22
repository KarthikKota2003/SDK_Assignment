
# SDK-Assignment
The assignment is done using django framework in python. 

The project has following paths for different functions :

/record : for recording data using pyAudio

/convert : for converting audio to text

/query : for querying data using openAI LLM

/play : for converting answer sent by openAI LLM and playing the audio

The output can be finally seen in output.mp3 file in the folder 

The openAI key can be changed in .env file of the environment

All the four paths have to be accessed to obtain answer as specified in the order above

For recording data pyAudio is used and it is later converted into text by Deepgram API

For playing result audio again Deepgram AI is used

All the views are class based and can be found in the views.py

Note : HTML page to render is answer is a bit slacky but the answer is perfect should the openAI API key work
