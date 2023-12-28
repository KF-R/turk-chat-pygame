### turk-chat-pygame conversation agent
<sub>_For the latest html/Flask version, please see https://github.com/KF-R/turk-chat_</sub>
<hr/>
As written, it expects `my_env.py` in your home directory; its contents defining API keys as follows:
```
API_KEY_OPENAI = '<insert_your_OpenAI_API_key_here>'
API_KEY_ELEVENLABS = '<insert_your_ElevenLabs_API_key_here>'
```

This approach uses async pygame as a front end for an OpenAI/ElevenLabs speech-to-speech chat system.

Run `converse.py` to launch.

Requirements:
```
numpy
pygame
Requests
sounddevice
pydub
PyAudio
openai
openai whisper
elevenlabs
```

