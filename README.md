# BlaB! G


BlaB! G is a PhoneGap app (Android/IOS) for [BlaB! AX](https://justblab.com), [BlaB! AX Pro](https://justblab.com), [BlaB! WS](https://justblab.com) and [BlaB! WS Pro](https://justblab.com chats. Your website visitors simply enter a chat code **once** and then join the chat. The app allows you to have native sound notifications via the PhoneGap media plugin - playing audio/video automatically is disabled in mobile browsers. The back button triggers a prompt to exit the app.

![Alt text](/bwsg.png "void")
![Alt text](/bwsge.png "void")

## Chat code

The chat code is the unique part of a `bit.ly` shortened URL of your BlaB! WS or BlaB! WS Pro URL ending with `?mobileapp=3`

* Create a bit.ly short link from `https://yourchat.com/chat/index.php?mobileapp=3`
* If the result is `bit.ly/2rC9gza` then the chat code **2rC9gza**
* `mobileapp=3` triggers a callback function that remembers the code in the app.

## Permissions

The app lists `phone`, `microphone` and `storage` - it is a PhoneGap media plugin requirement. You do not need to grant any permissions.


## License

MIT

## Links

* Website: https://justblab.com
* GitHub: https://github.com/uuencode/BlaB-G
* Google Play: https://play.google.com/store/apps/details?id=com.justblab.bwsg
