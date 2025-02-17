# ChatGPT SwiftUI iOS, macOS, watchOS, tvOS App

![Alt text](https://imagizer.imageshack.com/v2/640x480q90/922/hmlopw.png "image")

This is a native iOS, macOS, watchOS, tvOS App for interacting with ChatGPT built using SwiftUI and OpenAPI API. It used the leaked model and special prompt to access ChatGPT using Open AI Completions API endpoint.

## DISCLAIMERS!
The `ChatGPTAPI.swift` is updated frequently when new model is found. Expect breaking changes. Always read readme before updating or opening an issue.

Use this at your own risk, there is a possibility that OpenAI might ban your account using this approach! I don't take any responsibility.

## Separate SPM repo for API only
you can add dependency for [ChatGPTSwift](https://github.com/alfianlosari/ChatGPTSwift) to access the API only if you want to integrate into your own app

## UPDATE 6 - 9 Feb 2023

Add separate target for tvOS App

![Alt text](https://imagizer.imageshack.com/v2/640x480q90/924/3cnQLj.png "image")

## UPDATE 5 - 8 Feb 2023
The leaked model had been removed by OpenAI. Until a new model is found, i'll use the default `text-davinci-003`

## UPDATE 4 - 7 Feb 2023

Add separate target for watchOS independent App

![Alt text](https://imagizer.imageshack.com/v2/640x480q90/923/Hk89yV.png "image")

## UPDATE 4 - 5 Feb 2023
Add separate target for macOS Menu Bar App

![Alt text](https://imagizer.imageshack.com/v2/640x480q90/923/CufOj0.png "image")

## UPDATE 3 - 4 Feb 2023
Update to a much shorter prompt for triggering ChatGPT

## UPDATE 2 - 3 Feb 2023
It's working again after updating to the latest *model*

## UPDATE 1
At the time this video is published, the leaked model to access ChatGPT using Completion API endpoint had been taken down by OpenAI, so it won't work. But most of the concept should remain the same for building the application UI and state management. When the official API is released, you can simply update to use the public model and official endpoint for ChatGPT :) I'll also update the GitHub repo and create a follow-up video when it will be released in near future.

## Video tutorial
- [iOS YouTube](https://youtu.be/PLEgTCT20zU)
- [macOS YouTube](https://youtu.be/Wl1cDvwpJoE)
- [watchOS YouTube](https://youtu.be/DwXy0gKz1GY)
- [tvOS YouTube](https://youtu.be/7RQHG7GXJ_U)

## Requierements
- Xcode 14 
- Register at openai.com/api
- Create API Key
- Paste API key in ContentView where the ChatGPTAPI instance is declared
