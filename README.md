# GenAI/LLM Demo Apps hosted on HuggingFace Spaces

Welcome to the GenAI/LLM Demo Apps repository! This repository contains various demo applications showcasing the capabilities of Generative AI and Large Language Models.

  ## 1. <span style="color:blue;">Translator and Text Summarizer: English to French</span>



     Requirements:
     pip install transformers
     pip install torch
     pip install gradio

This application takes a long English text as input and outputs a translated summary in French.

![Capture d’écran (110)](https://github.com/Jimmy-Rais/HuggingFace_Spaces/assets/81222691/383be3f3-ae91-4371-9394-16380eafd645)

### Link to the demo app: https://huggingface.co/spaces/Jimmy-Rais/Translated_Text_Summary_English-To-French


 
  ## 2. <span style="color:blue;">Voice Cloning Multilingual Translator</span>


     
Requirements:
    pip install transformers
    pip install torch
    pip install gradio
    pip install TTS
Models used:
    Speech_to_text: distil-whisper/distil-small.en(HuggingFace)
    Machine_translation: facebook/nllb-200-distilled-600M(HuggingFace)
    Voice_cloning: tts_models/multilingual/multi-dataset/xtts_v2


This application takes an audio file(recorded or uploaded),clone the voice and output the speech translated in a desired language
with the cloned voice.

![Capture d’écran (114)](https://github.com/Jimmy-Rais/HuggingFace_Space/assets/81222691/bdcdb1fb-f268-424d-9309-d112f0877fad)


### Link to the demo app: https://huggingface.co/spaces/Jimmy-Rais/Voice-Cloning-MultiLingual-Translator


