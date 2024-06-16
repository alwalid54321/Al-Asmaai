## Al-Asma'i: The Digital Poet

![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![OpenAI](https://img.shields.io/badge/OpenAI-API-lightgrey)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-API-orange)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)

Al-Asma'i is an AI-powered project that brings Arabic poetry to life through multimedia generation. It converts textual poetry into a rich experience of generated images and background audio.
Features:

🖼️ Image generation for each verse using DALL-E
🔊 Audio narration of verses using ElevenLabs
📝 Verse explanations and illustrations using GPT
🎞️ Automatic video generation combining images and audio
🏰 Era classification of poems

# Hello, 🖋📜


We will be presenting the final project for the Data Science and Artificial Intelligence. Through this project, we use artificial intelligence to convert textual poetry into a multimedia experience of generated images and background audio. 🎨🔊

We are trying to explore Arabic poetry and shed light on its aesthetics and artistic depth in an innovative and engaging way.

first you should get the data from [here](https://huggingface.co/datasets/alwalid54321/Arabic_Poems) The data from (https://www.aldiwan.net/) and collected by: (https://huggingface.co/datasets/arbml/ashaar)


To achieve this, we will:

1. 💻 Install and set up the necessary AI libraries for generating images and audio, such as OpenAI and ElevenLabs, and you will find the data along with the main  file in Github.
2. 🔌 Prepare the application programming interfaces (APIs) to properly interact with these libraries.
3. 🎨🔊 Utilize these APIs to generate the appropriate images and audio for the Arabic poetry, and you may also need huggingface tikonizer API.
4. 📽️ Integrate the multimedia elements (images and audio) into a cohesive experience, synchronizing the image display with the audio playback.
5. 🎉Present this integrated poetic multimedia experience and emphasize the value it adds to Arabic poetry arts.

# How To Use:


Prerequisites:

Python 3.9+
OpenAI API key
ElevenLabs API key

Installation:

Clone the repository:
```
git clone https://github.com/yourusername/al-asmai.git
cd al-asmai
```

Install the required packages:
```
pip install -r requirements.txt
```

Set up your API keys as environment variables:
```
Copyexport OPENAI_API_KEY='your_openai_key_here'
export ELEVENLABS_API_KEY='your_elevenlabs_key_here'
```

Usage:

Prepare your poem data in a CSV format similar to poems.csv in the repository.
Run the main script:
```
python al_asmai.py
```
Enter the title of the poem when prompted.
The script will generate explanations, illustrations, audio, and images for each verse, and finally produce a video.

Contributing:
Contributions are welcome! Please feel free to submit a Pull Request.
License
This project is open source and available under the MIT License.
# Acknowledgments:
First for "Atheer" and "Lujain" for coming up with the idea

OpenAI for providing the GPT and DALL-E APIs

ElevenLabs for the text-to-speech API

All the great Arabic poets whose works inspire this project

by: **["alwalid54321"](https://github.com/alwalid54321)** and help from "Atheer" and "Lujain" 
