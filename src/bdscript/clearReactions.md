# $clearReactions
Removes reactions from the provided message.

## Usage
```
$clearReactions[channelID;messageID;emoji/!all]
```

### Parameters
- `channelID` `(Type: Snowflake || Flag: Required)`: The channel that the message belongs to.
- `messageID` `(Type: Snowflake || Flag: Required)`: The message to remove the reaction from.
- `emoji` `(Type: Emoji || Flag: Required)`: The emoji to remove from the message. Use `!all` to clear all reactions.
