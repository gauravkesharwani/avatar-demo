# Simli Deepgram AI Agent Technical Demo 

Combine Text-to-Speech, Speech-to-Text and Simli's Speech-to-Video into a conversational agent.



https://github.com/simliai/simli-deepgram-conversational-demo/assets/22096869/adecd52e-3384-44b3-9aa4-dd94d62dce57



## Demo features

- Capture streaming audio using [Deepgram Streaming Speech to Text](https://developers.deepgram.com/docs/getting-started-with-live-streaming-audio).
- Natural Language responses using an OpenAI LLM.
- Text to Speech conversion using [Deepgram Aura Text to Speech](https://developers.deepgram.com/docs/text-to-speech).
- Speech to Video avatars using [Simli LipsyncStream](https://docs.simli.com/)

## Quickstart

### Manual

Follow these steps to get started with this starter application.

#### Clone the repository

Go to GitHub and clone the repository.

#### Install dependencies

Install the project dependencies.

```bash
npm install
```

#### Edit the config file

Copy the code from `sample.env.local` and create a new file called `.env.local`.

```bash
DEEPGRAM_STT_DOMAIN=https://api.deepgram.com
DEEPGRAM_API_KEY=YOUR-DG-API-KEY
OPENAI_API_KEY=YOUR-OPENAI-API-KEY
NEXT_PUBLIC_SIMLI_API_KEY=YOUR-SIMLI-API-KEY
```

1. For `DEEPGRAM_API_KEY` paste in the key you generated in the [Deepgram console](https://console.deepgram.com/).
2. Set `DEEPGRAM_STT_DOMAIN` to be `https://api.deepgram.com`.
3. `OPENAI_API_KEY` should be an OpenAI API Key that can access the chat completions API.
4. `SIMLI-API-KEY` get your simli key from [Simli](https://www.simli.com/)

#### Build the application

Once running, you can [access the application in your browser](http://localhost:3000).

```bash
npm run build
```

```bash
npm start
```

## Author

[Deepgram](https://deepgram.com)

## License

This project is licensed under the MIT license. See the [LICENSE](./LICENSE) file for more info.
