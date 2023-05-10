[![My Skills](https://skillicons.dev/icons?i=nextjs,tailwind,react)](https://skillicons.dev)<a href="https://www.buymeacoffee.com/iguangzhengli" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

> ⚠️⚠️⚠️ Warning: Please understand that the https://chatfiles-ui.fly.dev web demo is temporarily unavailable as used up all the credits available in my free trial. and I am unable to recharge. If necessary, please run it locally yourself. Thanks.

# PDFChatbot

![Chatfiles](./doc/chatfiles.png)

**Upload your file and have a conversation with it.**


## How to use it

Open https://chatfiles-ui.fly.dev and chat with [Good Example](./doc/Example.md)

### How to run locally without limited
1. clone this repository.
2. create a .env file on root path.
3. put your OpenAI Key to .env file with OPENAI_API_KEY='your token'

run this project with docker compose.
```shell
docker compose up
```

open browser with http://localhost:3000

### chat with file
1. upload a file.
2. have a conversation with it.

### chat with GPT
1. send message without upload file.

## How to run locally
### chatfiles-ui

### how to deploy flyio
- [Deploy to fly.io](./doc/deploy-flyio.md)


## Feature

- [x] Chat with GPT-3.5
- [x] Chat with file by llama_index
- [x] Upload multiple files to one index, chat with multiple files.
