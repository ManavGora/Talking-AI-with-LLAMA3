# Real-Time AI Voice Assistant with LLAMA 3 and ElevenLabs
This project allows you to have natural, real-time conversations with an AI assistant using your voice. The assistant listens to your spoken questions, transcribes them, generates intelligent responses using LLAMA 3, and speaks back to you using ElevenLabs' text-to-speech capabilities.

Features
Real-time Transcription: Uses AssemblyAI for accurate and fast speech-to-text conversion.
Intelligent Responses: Powered by LLAMA 3, a state-of-the-art language model by Meta, for generating contextually relevant and informative responses.
Natural Voice Output: Leverages ElevenLabs' high-quality text-to-speech voices for lifelike interactions.
Easy Setup: Simple installation and configuration process.
Requirements
Python (3.7+): Make sure you have Python installed.
API Keys:
AssemblyAI API key (obtain from AssemblyAI website)
ElevenLabs API key (obtain from ElevenLabs website)
Installation
Clone the Repository:
Bash
git clone https://your-repository-url.git
cd your-repository-name
Use code with caution.
content_copy
Install Dependencies:
Bash
pip install ollama "assemblyai[extras]" elevenlabs mpv
Use code with caution.
content_copy
Download Llama 3 Model:
Bash
ollama pull llama3
Use code with caution.
content_copy
Install portaudio:
Debian/Ubuntu: apt install portaudio19-dev
MacOS: brew install portaudio
Set API Keys:
Create a file named .env in the project directory and add the following lines, replacing your_api_key with your actual keys:
ASSEMBLYAI_API_KEY=your_assemblyai_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key
Usage
Run the Script:
Bash
python your_script_name.py
Use code with caution.
content_copy
Start Talking: The assistant will begin listening for your voice.
Ask Questions: Speak naturally, and the assistant will respond.
Customization
Voice Selection: Change the voice in the AI_Assistant class by modifying the voice argument in the client.generate method.
LLAMA 3 Model: You can experiment with different LLAMA 3 models or fine-tune it for your specific needs.
Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests.
This project enables real-time voice conversations with an AI assistant, using AssemblyAI for speech-to-text, LLAMA 3 for generating responses, and ElevenLabs for text-to-speech conversion.

This project allows you to have natural, real-time conversations with an AI assistant using your voice. The assistant listens to your spoken questions, transcribes them, generates intelligent responses using LLAMA 3, and speaks back to you using ElevenLabs' text-to-speech capabilities.

Features
Real-time Transcription: Uses AssemblyAI for accurate and fast speech-to-text conversion.
Intelligent Responses: Powered by LLAMA 3, a state-of-the-art language model by Meta, for generating contextually relevant and informative responses.
Natural Voice Output: Leverages ElevenLabs' high-quality text-to-speech voices for lifelike interactions.
Easy Setup: Simple installation and configuration process.
Requirements
Python (3.7+): Make sure you have Python installed.
API Keys:
AssemblyAI API key (obtain from AssemblyAI website)
ElevenLabs API key (obtain from ElevenLabs website)
Installation
Clone the Repository:
Bash
git clone https://your-repository-url.git
cd your-repository-name
Use code with caution.
content_copy
Install Dependencies:
Bash
pip install ollama "assemblyai[extras]" elevenlabs mpv
Use code with caution.
content_copy
Download Llama 3 Model:
Bash
ollama pull llama3
Use code with caution.
content_copy
Install portaudio:
Debian/Ubuntu: apt install portaudio19-dev
MacOS: brew install portaudio
Set API Keys:
Create a file named .env in the project directory and add the following lines, replacing your_api_key with your actual keys:
ASSEMBLYAI_API_KEY=your_assemblyai_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key
Usage
Run the Script:
Bash
python your_script_name.py
Use code with caution.
content_copy
Start Talking: The assistant will begin listening for your voice.
Ask Questions: Speak naturally, and the assistant will respond.
Customization
Voice Selection: Change the voice in the AI_Assistant class by modifying the voice argument in the client.generate method.
LLAMA 3 Model: You can experiment with different LLAMA 3 models or fine-tune it for your specific needs.
Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests.
