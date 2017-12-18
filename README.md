# BlaB! WS G


BlaB! WS G is a PhoneGap app (Android/IOS) for [BlaB! WS](https://justblab.com) and [BlaB! WS Pro](https://justblab.com) websocket chats. Your website visitors simply enter a chat code **once** and then join the chat. The app allows you to have native sound notifications via the PhoneGap media plugin - playing audio/video automatically is disabled in mobile browsers. The back button triggers a prompt to exit the app.

![Alt text](/bwsg.png "void")
![Alt text](/bwsg2.png "void")

## Chat code

The chat code is the unique part of a `goo.gl` shortened URL of your BlaB! WS or BlaB! WS Pro URL ending with `?mobileapp=3`

* Create a goo.gl short link from `https://yourchat.com/chat/index.php?mobileapp=3`
* If the result is `goo.gl/D6FR7e` then the chat code **D6FR7e**
* `mobileapp=3` triggers a callback function that remembers the code in the app.

## Permissions

The app lists `phone`, `microphone` and `storage` - it is a PhoneGap media plugin requirement. You do not need to grant any permissions.


## License

MIT

## Links

* Website: https://justblab.com
* GitHub: https://github.com/uuencode/BlaB-WS-G
* Google Play: https://play.google.com/store/apps/details?id=com.justblab.bwsg`
