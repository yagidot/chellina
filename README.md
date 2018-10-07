# Chellina Bot Messenger

#### Prefix or Comand list
```command list:
-----
* Text-to-speech:
VN:
    say <text>
jap (japanese):
    say jp <text>
eng (english):
    say en <text>
korean:
    say ko <text>
for example: say en hello
-----
* play music:
play <youtube link>
_ or
sing <youtube link>

for example: play https://youtu.be/2ekJDfX_13s
_____
* auto responder:
text:
    <a> -> <b>
    for example: hello -> hi
Place multiple answers to the question (random):
    <a> -> <b> | <c> | <d>
    for example: 1 + 1 = -> 2 | 3 4
sticker:
    set sticker <a>
    for example: set sticker hello
_____
* delete a command (not the default)
    del <a>
    for example: del hello
_____
* encoding a piece of text:
    encode <text>
* decryption:
    decode <code>
* Decode and execute:
    parse <code>
-----
    send sticker, @sticker, <(") or 🍀
* send any sticker.
_____
    .cmd
* View all of the commands placed in the group
-----
    check connection
* View connection status
-----
    prefix
* see prefix
-----
* View group member ratings (currently in error)
    ranking
-----
    ping
- pong
-----
    .lenny
-> (͡ ° ͜ʖ ͡ °)
```

#### Install
1. `npm install`
2. open file on dir `user/config.json` and `utils/account.json` replace `username` and `password` , and replace adminid on `user/config.json` to Your profileid Admin 
3. open file on dir `utils/main.js` and replace line `541` and `543` to profile id your bot


###### 2018 Iqbal Rifai, MIT License
