# Groq2API

## Installation

```bash

docker run -d -p 8080:8080  ghcr.io/star-studio-develop/groq2api:latest

```

## Usage

```bash

curl --request POST \
  --url http://127.0.0.1:8080/v1/chat/completions \
  --header 'Authorization: Bearer change-it-to-your-refresh-token' \
  --data '{
  "messages": [
    {
      "role": "user",
      "content": "hi"
    }
  ],
  "model": "mixtral-8x7b-32768",
  "max_tokens": 500,
  "stream": true
}'

```

![image](https://github.com/Star-Studio-Develop/Groq2API/assets/148524140/adedf992-864a-47b1-9201-d53717befd4a)

