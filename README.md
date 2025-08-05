# A JavaScript Wrapper for Newgrounds API 3.0

# Features
- Small self contained wrapper for Newgrounds API 3.0 calls
- Functions provided for medals and soreboards
- Medal popup display rendering with icons
- Escaped emojis can be used in medal names and descriptions
- Encryption is set up for AES-128 Base64 encryption
- [Uses CryptoJS for encryption](https://github.com/brix/crypto-js)

# Example Usage
```
Newgrounds.Init(appID, encryptionCipher);
Newgrounds.UnlockMedal(85749);      // Parameters: (Medal ID)
Newgrounds.PostScore(15159, 12345);     // Parameters: (Scoreboard ID, score value)
```
# Optional Update/Render for Medal Popups
```
Newgrounds.Update(timeDelta);
Newgrounds.Render(canvasContext, drawSize);
```
