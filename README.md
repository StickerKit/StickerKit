# StickerKit Documentation

StickerKit is a web app along with an iOS SDK to make it easy for you to create Sticker Apps.

### Steps to creating a iMessage Sticker App using StickerKit
- Create an account at http://stickerkit.io.
- Upload your stickers onto our website.
- Download our [Example Sticker App](https://github.com/StickerKit/StickerKit-iMessage-Example-App), input your Project Key, and Run the App!

For a step-by-step tutorial, check out this guide: https://medium.com/@dmathewwws/using-stickerkit-to-build-an-imessage-sticker-app-28d301ee745d#.u7alqylza

## StickerKit's iOS SDK

If you would like to add StickerKit to an existing iMessage Sticker App, we recommend using StickerKit's iOS SDK. It contains code that downloads and caches your stickers from StickerKit's API, and has analytics tracking already built into it.

You can find StickerKit's iOS SDK here: https://github.com/StickerKit/StickerKit-iOS-SDK/

## StickerKit Rest API

Builing an Android or Web App and want to get your Stickers? 

Use StickerKit's RESTful API.

https://app.stickerkit.io/api/v1/<project_id>

Whenever a sticker is added / re-ordered / deleted for your project, the data from that endpoint will be updated.
