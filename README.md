# AI-Video-Translation

(This project is not maintained anymore, feel free to fork and modify it!)<br>

A simple Google Colab notebook which can translate an original video into multiple languages along with lip sync.

<b>How it works?</b>

1: Upload video<br>
2: Extract audio and get text from the audio (OpenAI Whisper)<br>
3: Translate the text (Google Translate)<br>
4: Synthesize the translated text with the original voice. a.k.a Voice Cloning (coqui-ai TTS)<br>
5: Lip sync the synthesized audio with the original video clip (OpenTalker video-retalking || Wav2Lip)<br>

<i>The links for the repos mentioned above are given in the notebook itself.</i>
