# force align

the script is based on [whisperer](https://github.com/johnafish/whisperer). it adds support for german with a multilangual model for [WAV2NET2](https://pytorch.org/audio/stable/pipelines.html#torchaudio.pipelines.Wav2Vec2ASRBundle). 

transcription is done via [whisper](https://github.com/openai/whisper) from OpenAI.
Most of the code is very well explained here: [pytorch tutorial](https://pytorch.org/tutorials/intermediate/forced_alignment_with_torchaudio_tutorial.html) on forced alignment to generate word-level .srt captions

## Usage

Install ```pip install -r requirements.txt```, and use ```python gernerate.py <filename.wav>```
