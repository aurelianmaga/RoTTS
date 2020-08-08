# Romanian Text To Speech

## Introduction

A REST service for generating text to speech for Romanian language. The web interface it's available at:  http://www.t2s.ro

## Usage

To convert text to speech make the following call

```

POST https://www.t2s.ro/tts
Authorization: 36e28220-6514-4063-a6ed-6e75acd33c7a
Content-Type: application/vnd.tts+json
Accept: audio/wav

{
  "text": "Bună, aici convertești text la voce în limba română."
}
```

## Acknowledge

This project was made posible by building on top of [Tacotron-2](https://github.com/aurelianmaga/Tacotron-2.ro) and [SWARA Speech Corpus](https://speech.utcluj.ro/swarasc/).
