---
layout: article
category: eliteva
subject: token syntax
description: An overview of token syntax
navigation: eliteva
---

# Token syntax with EliteVA

## VoiceAttack tokens

Tokens can been seen as variables in VoiceAttack. Tokens hold dynamic pieces of information that can be requested in logical expressions and in text-to-speech functions.

Every token has a type of value. VoiceAttack differentiates between six different types of values:

| Type | Value example |
| ---- | ------------- |
| Booleans | `true` `false` |
| Dates | `4/6/2015 12:01:52 PM` |
| Decimals | `245.2` `0.4245` |
| Integers | `36` `4335` `-357803` |
| Small integers | `2` `-5` `1` |
| Text | `John` `C:\User\James\Desktop` |

## Token identifier

Every token has an unique identifier within VoiceAttack with which the value of a token can be requested. The identifier of a token is build up out of two parts; the token type and the token name surrounded by curly braces. For example: `{BOOL:ItIsRaining}` is a boolean token with the the name *ItIsRaining*.

| Type | Example |
| ---- | ------ |
| Booleans | `{BOOL:IsInGame}` |
| Dates | `{DATE:StartedPlayingAt}` |
| Decimals | `{DEC:KillPercentage}` |
| Integers | `{INT:GamesWon}` |
| Small integers | `{SMALL:HotbarSlot}` |
| Text | `{TXT:InGameName}` |