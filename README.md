
![Logo](https://github.com/rskakadiya/Personal-Assistant-Flutter/blob/master/assets/images/virtualAssistant.png)


# Personal Assistant - Flutter

The "Personal Assistant" project in Flutter harnesses the capabilities of ChatGPT and DALL-E API, creating a mobile app that offers users an interactive digital assistant. Users can have natural language conversations with the AI, ask questions, and even describe images to generate corresponding visual content. This project merges cutting-edge AI technology with the Flutter framework for a seamless and engaging user experience.


## Tech Stack

**Client:** Flutter, Dart

**Pub Packages:** [http](https://pub.dev/packages/http), [speech_to_text](https://pub.dev/packages/speech_to_text), [flutter_tts](https://pub.dev/packages/flutter_tts), [animate_do](https://pub.dev/packages/animate_do)
## API Reference

```http
  lib/secrets.dart
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `openAIAPIKey` | `string` | **Required**. YOUR OpenAI KEY HERE |

[ChatGPT API Docs](https://platform.openai.com/docs/api-reference/chat)

[DALL-E API Docs](https://platform.openai.com/docs/api-reference/images)

If you don't have an API Key then [CREATE HERE](https://platform.openai.com/account/api-keys)

## Features

- Live previews
- Cross-platform
- Smooth Animations
- Speak back when response comes from ChatGPT API
- Responses smartly between DALL-E Image & ChatGPT texts
## Screenshots

Not Listening

![Not Listening](https://github.com/rskakadiya/Personal-Assistant-Flutter/blob/master/screenshots/not_listening.png)


Listening

![Listening](https://github.com/rskakadiya/Personal-Assistant-Flutter/blob/master/screenshots/listening.png)

## Sounds

We need to add three sounds for iOS. In Android it is added automatically

[Speech To Text Cancel](https://github.com/rskakadiya/Personal-Assistant-Flutter/blob/master/assets/sounds/speech_to_text_cancel.m4r), [Speech To Text Listening](https://github.com/rskakadiya/Personal-Assistant-Flutter/blob/master/assets/sounds/speech_to_text_listening.m4r), [Speech To Text Stop](https://github.com/rskakadiya/Personal-Assistant-Flutter/blob/master/assets/sounds/speech_to_text_stop.m4r)


## Fonts

[Cera Pro](https://github.com/rskakadiya/Personal-Assistant-Flutter/tree/master/assets/fonts)

## Support

For support, email rinkal@cynuxsolutions.com

